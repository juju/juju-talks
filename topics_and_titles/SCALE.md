# Submissions to the Southern California Linux Expo

List of submissions and text for SCALE:

## Writing your First Juju Charm 

Bring your laptop! In this session we will do the following things:

- Install and configure Juju (we'll also provide you with free-to-use Amazon credentials.
- Write a charm from scratch
- Show you how to leverage existing charm layers and interfaces so you can do less work.
- Show you how to share your charm with others so they can use your stuff.

Audience: Sysadmins and devops

Requirements for following along:

- A laptop running Ubuntu (or you can build Juju from golang source if you're not using Ubuntu)
- A GPG key on a public keyserver if you want to use our free AWS credentials
- An AWS, GCE, Joyent, or Azure account

## Real-world Big Data workloads in the cloud

There's a flood of open data out there from organizations and governments large and small.  With such easy access to this, solving common big data problems seems simpler than ever before.  Got a problem with traffic, weather, or money?  Analyze the right datasets, and you just might learn that 2pm on a sunny Tuesday afternoon is the best time to drive to the bank.  Thanks Big Data!

The rub with trying to solve these problems is in the deployment and configuration of all the services that need to work together to get to an answer.  Wouldn't it be great if there was an easy way to model a Big Data platform (complete with ingestion, processing, and visualization components), stand that up in a cloud, and get down to business?  "Yes" is the right answer, and fortunately, Juju does just that.

In this talk, we'll cover some of the Big Data services available in the Juju ecosystem (Hadoop, Spark, Kafka, Zeppelin, etc) and then discuss how these can be bundled together as a platform for grinding on Big Data problems.  We'll then demo some of the real-world problem-solving bundles that we've found most popular, including realtime log analytics and finding meaning in financial market data.  We may even tell you which is better:  Emacs or vi.  (just kidding, you don't need Hadoop to know it's vi).

This talk is intended for an intermediate audience and will best serve people that have a basic understanding of common components in a Big Data platform.  If I say "NameNode", you should not need to google that.  Ideally, you've experienced the pain of standing up Big Data first hand, or at least heard of someone that changed careers because configuring their Big Data cluster was that awful.

## Easy Big Data workloads in the Cloud with Juju

This talk is for:

People who have to manage multiple services in the cloud (public or private). This can be AWS, HP Cloud, OpenStack, Microsoft Windows Azure, your VPS provider, or your own pile of machines. Any Ubuntu machine with an open SSH port can work. 
You're probably a system administrator or developer, or you're a data guy who is on your own without either of these two to help you.
This talk will cover the following things: What we'll show you:

Real life running services in a cloud, no mockups or demos, what you see here is how the tool works in real life.
Take you through some devops workflows so you can test locally (and cheaply) and iterate before spending money in production.
Juju isn't configuration management, it's service orchestration - so we'll have some examples on hand of real-life bundles and combinations of these services that you can modify and reuse for your own needs. 
You can also follow along! The audience can participate by installing Juju if they like, depending on network conditions.


