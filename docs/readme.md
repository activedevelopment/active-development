
# one

This is the _internal_ readme file - as opposed to the top-level README, which
is written explaining _why_. This file is more of a to-do list, or
brainstorming doc.


## Looking at Docker's Role in Active Development

### three

#### Pros

- Do not have to contaminate host machine with all sorts of tools that get
  outdated quickly.
  - Therefore, aren't wasting time updating and reconfiguring all the time.

#### Cons

- Having one more layer adds to complexity (or at least the learning curve.)
  - Hopefully, the time required lessens over time.
  - Hopefully, time saved is greater than otherwise.

#### Questions

- Can it be used to solve the C++ package management problem?
- Should I use one giant uber-container?
- How much does it help active development?
- Can you do multi-language?
  - For example, use NodeJS for glue-ish network, and Golang for primary?

#### Investigate

- Can the video be accessed directly from inside the container (without using X)?
- Can this technique be used so Redis can act as a cross-invoke data persistence?
- Does it work for Java?
  - Android?
  - Android C++?
- Write C++, wrap with JNI, Python, NodeJS, Golang, etc.

## Make Specific environments

- MQ -> Raylib
- MQ -> React
- Use GPU (for compute)
- Golang container build-magic

- Maybe
  - Golang + Lorca / NodeJS (for React) / NextJS

## Learn

Make specific dev environments to learn how to:

- Kafka
- Kafka for Event Sourcing
- k8s / Rancher
- Figure out the 'best' MQ
- What makes PostGres so well-liked?
- Neo4J
- GraphQL
- Secrets




