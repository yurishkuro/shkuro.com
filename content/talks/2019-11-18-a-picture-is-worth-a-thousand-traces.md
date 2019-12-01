---
title: "A Picture is Worth a 1,000 Traces"
date: 2019-11-18
draft: false
venue: Observability Practitioners Summit @ KubeCon NA 2019
video: https://youtu.be/rMSqgSFuBi0
---

**Event**: [{{< param venue >}}](https://observabilitysummit.com)

**Date**: November 18, 2019

**Speakers**: Yuri Shkuro, [Steve Flanders](https://twitter.com/smflanders)

**Video**: [YouTube]({{< param video >}}) (or below)

A single trace can reveal many things: network latencies, time spent in databases, a service spinning idly, etc. but finding the right trace among billions that demonstrates a problem in a large distributed application is very hard. By looking at traces in aggregate, we can eliminate the need to state and validate hypotheses. In this talk I describe a system deployed at Uber, built on top of Jaeger, of course, that learns the typical system behavior in production and uses graph comparison visualizations to highlight the differences between normal and failed requests, in order to assist SREs with fast failure attribution during outages and improve time to mitigation.

{{< youtube rMSqgSFuBi0 >}}
