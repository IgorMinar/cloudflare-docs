---
pcx-content-type: concept
title: About drand
weight: 2
---

# About the drand project

The drand project aims to address the current lack of services providing distributed public randomness. Distributed to increase the resilience and trustworthiness, drand provides a standalone randomness-as-a-service network that is application agnostic. This is similar to how NTP networks serve timing information across the globe.

Drand follows the [KISS principle](https://en.wikipedia.org/wiki/KISS_principle). It relies on well-researched cryptographic building blocks and open-source software design principles and libraries, such as protobuf and gRPC, to ensure high performance and interoperability. Drand also attempts to use sane security defaults, such as having TLS enabled by default.

Beyond that, drand adds new features important for its practical deployment, such as being able to securely add and remove members of the network through [resharing](https://ieeexplore.ieee.org/document/1183515) while keeping the same shared public key necessary for randomness verification.