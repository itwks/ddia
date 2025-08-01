---
title: "PART I: Foundations of Data Systems"
weight: 100
breadcrumbs: false
---

The first four chapters go through the fundamental ideas that apply to all data sys‐ tems, whether running on a single machine or distributed across a cluster of machines:

1. [Chapter 1](/en/ch1) introduces the terminology and approach that we’re going to use throughout this book. It examines what we actually mean by words like *reliabil‐ ity*, *scalability*, and *maintainability*, and how we can try to achieve these goals.

2. [Chapter 2](/en/ch2) compares several different data models and query languages—the most visible distinguishing factor between databases from a developer’s point of view. We will see how different models are appropriate to different situations.

3. [Chapter 3](/en/ch4) turns to the internals of storage engines and looks at how databases lay out data on disk. Different storage engines are optimized for different workloads, and choosing the right one can have a huge effect on performance.

4. [Chapter 4](/en/ch4) compares various formats for data encoding (serialization) and espe‐ cially examines how they fare in an environment where application requirements change and schemas need to adapt over time.

Later, [Part II](/en/part-ii) will turn to the particular issues of distributed data systems.


## Index

- [1. Reliable, Scalable, and Maintainable Applications](/en/ch1)
- [2. Data Models and Query Languages](/en/ch2)
- [3. Storage and Retrieval](/en/ch3)
- [4. Encoding and Evolution](/en/ch4)