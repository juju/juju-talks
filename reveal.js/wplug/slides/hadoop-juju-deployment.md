##  How about this instead?

#### Deploy Hadoop

```
juju deploy hadoop hadoop-master
juju deploy hadoop hadoop-slavecluster
juju add-unit -n 2 hadoop-slavecluster
```

#### And connect them together

```
juju add-relation hadoop-master:namenode hadoop-slavecluster:datanode
juju add-relation hadoop-master:jobtracker hadoop-slavecluster:tasktracker
```

#### And scale the workers

```
juju add-unit hadoop-slavecluster
```
