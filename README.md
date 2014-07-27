#Orisi - Distributed Oracle System

Orisi is a distributed system of anonymous oracle nodes which safely validates distributed contracts which use external state for their conditions. Although validation outside the blockchain is possible with Bitcoin, it is very insecure as it relies on one sole external source for validation. Orisi solves this dependency problem by creating a distributed network in which the majority of oracles have to agree to have a transaction validated. This distributed system makes it exponentially harder to bribe or otherwise influence the oracles, and is still able to validate a contract if one or more of the oracles fail.

* [Read the White Paper](https://github.com/orisi/wiki/wiki/Orisi-White-Paper) - Introduction to Orisi
* [Performing a timelock transaction](https://github.com/orisi/wiki/wiki/Performing-a-Timelock-transaction) - install a client and try out example transactions
* [Understanding timelock](https://www.youtube.com/watch?v=boPW1FwNu4c) - a Khan-academy style, 8-minute video explaining what happens when you launch the Timelock client, and the way Orisi works in general.

--------------------

* [Installing the oracle node](https://github.com/orisi/wiki/wiki/Installing-the-oracle-node) - Instructions for setting up an oracle node

---------------------

* [src/oracle](./src/oracle) - Oracle node source

* [src/client](./src/client) - Reference client source

---------------------

* Please keep in mind that both client and oracle are in very early alpha versions and are very unstable. We encourage you to use them and test them. Please post any issue with [Issue Tracker](https://github.com/orisi/orisi/issues). If you have any fixes do not hesitate to post [Pull Requests](https://github.com/orisi/orisi/pulls)
