# Surviving with Config Management in a post Immutable Apocalypse

In a talk based out of minor absurdity (as tribute to Gary Bernhardt), I offer the following: It’s the 1950’s. Because Fallout came out and did a great job of setting this up. I have my handy dandy personal data companion complete with Infra as code of choice (many represented here). The landscape is foreign outside of the vault. Nothing but application containers and disposable constructs. Failing applications causing systems to go astray or offline.

We’ll suit up, prepare ourselves for a lifetime of wandering a post-nuclear wasteland filled with unchanging infrastructure, for better or worse. (Remember, it’s the apocalypse) and setup our own personal paradise in the wasteland. 



# Config Management and Containers

### If all containers are equal, why are you proposing I use [chef|puppet|ansible|salt] and containers again?

Today’s perception of containers is primarily focused on the “Dockeriziation” of application containers. Or the forward progression pattern of adopting microservice architectures to achieve immutable results. Meaning - Config Management is a direct antipattern.. 

The proper answer here is that we can achieve proper microservice patterns, in familiar environments using the tools we’ve had on hand all along. Bringing this knowledge into containers has real world benefits and I’ll show you how.

Attendee’s should expect to learn about:

Container provisioning
Container enlistment
Tooling that supports this workflow
Config Managed container density
Config managed container snapshots and migrations
