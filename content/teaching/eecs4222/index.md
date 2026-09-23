---
title: EECS 4222
summary: Distributed Computing Systems

tags:
- undergrad
date: "2018-01-01T00:00:00Z"

show_date: false

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Distributed Systems
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/HamzehKhazaei
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

This is an introductory course in Distributed Computing Systems. This course is the study of how to design and
implement a computer system where the state of the system is divided over multiple computing nodes. More
specifically, this course teaches design and implementation techniques that enable the building of functional,
usable, fast, fault-tolerant and scalable distributed systems. To make the issues more concrete, the class
includes two projects requiring significant design and implementation which enable students to gain practical
experience in designing, implementing, and debugging real distributed systems.

In this course we use the Go programming language, which was designed for implementing distributed systems.
For the most part, students learn this language on their own, with the TAs covering the fundamentals of Go and
then practicing the language through the course projects during the biweekly labs.

Topics include distributed communication models (e.g., sockets, remote procedure calls, distributed shared
memory), distributed synchronization (clock synchronization, logical clocks, distributed mutex), distributed
file systems, replication, consistency models, fault tolerance, QoS and performance, scheduling, concurrency,
agreement and commitment, Paxos-based consensus, MapReduce and NoSQL datastores, decentralized systems, cloud
infrastructures, microservices, and serverless computing.

By the end of this course, students will be able to:
- Apply communication protocols such as remote procedure calls, taking into account control semantics and
  language limitations; implement serialization and de-serialization; apply the end-to-end argument in real
  systems.
- Analyze data caching and one-copy semantics, cache consistency protocols and implementation tradeoffs, and
  temporal and spatial locality.
- Trace failures in distributed systems using empirical studies such as fail-fast and Byzantine failures, and
  identify fundamental limits of failure resilience.
- Explain how to achieve consensus using unanimity (two-phase commit) and majority (leader election, Paxos).
- Design and implement highly available systems using the basic concepts of replication with the latest
  paradigms and design patterns in distributed cloud systems.

