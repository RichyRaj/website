---
layout: default
keywords:
title: Distributed Systems
description: "<p>Most software is now distributed in some sense. This course is meant to serve as an introduction to distributed systems, emphasizing techniques for creating functional, usable, and high-performance distributed systems.</p>

<p>This course aims to: (1) provide students with an understanding of the principles and techniques behind the design of distributed systems, such as locking, concurrency, scheduling, and communication across the network. (2) provide students with practical experience designing, implementing, and debugging real distributed systems.</p>

<p>Major themes covered in this course include scarcity, scheduling, concurrency and concurrent programming, naming, abstraction and modularity, imperfect communication and other types of failure, protection from accidental and malicious harm, optimism, and the use of instrumentation and monitoring and debugging tools in problem solving. As the creation and management of software systems is a fundamental goal of any undergraduate systems course, students will design, implement, and debug large programming projects.</p>"

buttons: [syllabus, piazza]
micro_nav: true
---
## Note regarding waitlist
440: If you are on the waitlist, we encourage you to attend the first few classes. Typically there is a lot of churn in enrollment in the beginning of the semester. It is likely that the waitlist will get cleared in the initial few weeks. Of course, this cannot be guaranteed since it depends on other enrolled students dropping the course. <br>
640: We expect the waitlist for 640 to be processed by July 17 2020.
## Course Information

- This semester (Fall 2020), the course will follow closely along the previous Fall versions of this course. In particular, the projects will use the Go programming language.
- This semester (Fall 2020), _tentatively_ lectures are going to be on Tuesdays and Thursdays 10:30-11:50 AM in GHC4401.
- All class communication happens on the 15-440 Piazza forum. For longer discussions with TAs and to get help in person, we strongly encourage you to come to office hours. If you need to contact us via email, please email individual TAs.
- The course content and deadlines for all assignments will be listed in our syllabus.

<!-- Course Staff -->
{% include staff.html %}


## Prerequisites

Because this course has a big project component, you must be proficient in C and programming on UNIX systems. We will use the [Go programming language](https://golang.org/) throughout the term. It is required that you have taken 15-213 and gotten a "C-" or higher since many of the programming skills you will need are taught in that course. **However, if you received a C in 15-213, you must meet with your academic advisor to discuss your background before taking 15-440/640, perhaps taking an additional course to sharpen your systems skills. Your advisor must email us approval and an explanation of why you have sufficient background to take 15-440/640.**

## Learning Objectives

After this course, students will have learned to...

- Implement and structure distributed systems programs.
- Write programs that can interoperate using well-defined protocols.
- Debug highly concurrent code that spans multiple programs running on multiple cores and machines.
- Reason about distributed algorithms for locking, synchronization and concurrency, scheduling, and replication.
- Use standard network communication primitives such as UDP and TCP.
- Understand the general properties of networked communication necessary for distributed systems programming in clusters and on the Internet.
- Employ and create common paradigms for easing the task of distributed systems programming, such as distributed filesystems, RPC, and MapReduce. Be able to clearly elucidate their benefits, drawbacks, and limitations.
- Identify the security challenges faced by distributed systems programs.
- Be able to select appropriate security solutions to meet the needs of commonly encountered distributed programming scenarios.

## Course Policies

For all of the course policies, including grading policies, please head to the [syllabus]({{ site.baseurl }}/syllabus).
