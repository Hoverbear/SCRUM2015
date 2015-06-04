---
layout: page
title: Call for Papers
---

![Soaring in the clouds](/public/img/jet-sky.jpg)

> Do you soar in the clouds? Are you a master of distributed replication? A seeker of eventual consistency?

Middleware is often constructed from components and interconnects spanning a wide range
of programming languages and frameworks, executing in environments with unpredictable
latencies, unknown availability, and concurrent demand for resources. Designing, deploying,
and reasoning about consistency models (e.g., serializability, snapshot isolation, 
eventual consistency, etc.) and invariants (e.g., partial order, equivalence, or generic guarantees,
etc.) involves subtle tradeoffs in terms of fault tolerance, performance, scalability and programmability.

This topic area will bring together researchers and practitioners facing these tradeoffs in the
context of modern middleware, which must allow for fluid placement of computation and
data between everything from sensors to multi-domain clouds. In such environments, the
problem of maintaining consistency is exacerbated by widespread replication — including
client - managed data. We envision participants interested in a range of questions in programmability and consistency, including:

* What are suitable future programming models for consistency in middleware? What logical abstractions for consistency are useful and tolerable?
* Which low-level information (e.g., bandwidth, latency or location) should show through to the programmer, to allow the middleware to adapt its consistency strategy effectively?
* What consistency models are used/effective in current middleware and why?
* Which distributed consensus protocols (e.g., RAFT, Paxos, and ZooKeeper) are practical in middleware, when and why?
* Can design patterns help comprehensibility of consistency models?
* What are the most effective/promising deployment techniques for weak consistency, strong consistency, and strategies that fall somewhere in between?
* What are the most critical factors for middleware developers to consider when selecting between competing consistency models?
* How can middleware extend consistency ”to the edge”?

Tentative workshop paper submission and notification deadlines:

1. August 20, 2015 – Paper Submissions Deadline
2. September 20, 2015 – Notifications
3. October 3, 2015 – Camera Ready Papers

