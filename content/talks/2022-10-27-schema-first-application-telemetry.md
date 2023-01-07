---
title: "Schema-first Application Telemetry"
date: 2022-10-27T10:00:00-05:00
draft: false
venue: SRECon22 Europe/Middle East/Africa
video: https://youtu.be/z7rRIH-UYxs
slides: https://speakerdeck.com/yurishkuro/schema-first-application-telemetry
---

**Event**: [{{< param venue >}}](https://www.usenix.org/conference/srecon22emea/presentation/shkuro)

**Date**: October 27, 2022

**Speakers**: Yuri Shkuro

**Video**: [YouTube]({{< param video >}}) (or below). **Slides**: [SpeakerDeck]({{< param slides >}})

The journey to cloud-native observability starts with basic telemetry gathering: metrics, logs, events, traces, etc. Teams soon realize that they are collecting a lot of fragmented telemetry data that is difficult to interpret without additional metadata. Instead, users often need to rely on tribal knowledge about telemetry datasets. The missing metadata can range from simple things like descriptions, types, and units of measure, to machine-readable semantic data identifying joinable dimensions, privacy policies, etc. In this talk we present a schema-first approach to application telemetry, including an improved developer experience that minimizes the initial overhead of authoring telemetry signals, and the schema definition language based on Thrift IDL with annotations and rich types that capture semantic meaning and other metadata suitable for automated processing. We contrast this approach with the existing techniques popular in the industry, including the OpenTelemetry Semantic Conventions, to demonstrate the benefits and the trade-offs.

{{< youtube "z7rRIH-UYxs" >}}
