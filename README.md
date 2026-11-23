# \[Work In Progress\] AMWA IN-007: DMF Security: Assets & Requirements
[![Lint Status](https://github.com/AMWA-TV/in-007/actions/workflows/lint.yml/badge.svg)](https://github.com/AMWA-TV/in-007/actions/workflows/lint.yml)
[![Zensical Render Status](https://github.com/AMWA-TV/in-007/actions/workflows/docs.yml/badge.svg)](https://github.com/AMWA-TV/in-007/actions/workflows/docs.yml)
[![License](https://img.shields.io/github/license/AMWA-TV/in-007)](https://github.com/AMWA-TV/in-007/blob/HEAD/LICENSE)
[![Issues](https://img.shields.io/github/issues/AMWA-TV/in-007)](https://github.com/AMWA-TV/in-007/issues)

This repository holds the source of a work artifact published as an **[AMWA Increment (IN)](https://specs.amwa.tv/in-index)** from the [Advanced Media Workflow Association](https://amwa.tv)

<!-- INTRO-START -->

### What does it do?

- Identifies the DMF components and information assets that are relevant to security.
- Considers those assets in terms of confidentiality, integrity, availability, authenticity, and non-repudiation.
- Proposes an initial set of security requirements for the design and operation of a DMF.

### Why does it matter?

- DMF processes media across hosts, workloads, and services, so security failures can affect media, control, and production availability.
- Making security assumptions and requirements explicit gives designers, implementers, and operators a shared basis for review.
- It highlights open questions, including media-payload encryption and security across multiple Clusters.

### How does it work?

- Organises the scope around assets such as Hosts, Media Workloads, Media Functions, Domains, Flows, and Replicators.
- Assesses those assets against confidentiality, integrity, availability, authenticity, and non-repudiation.
- Sets out requirements covering identity and access control, configuration, logging, hardening, isolation, availability, and recovery.

This work artifact is published as an **AMWA Increment (IN)**. Increments are intended to make public the ongoing progress of a working group without locking decisions into a formal specification. While the technical details contained in this repository do not constitute a stable or finalized specification, readers should note that Increments are Draft Specifications as defined in the AMWA IPR Policy. The provisions of the policy apply, including the requirement for early disclosure. You can expect the content to evolve incrementally based on ongoing testing, consensus-building, and community input. Public review is encouraged! Please post an Issue to the Repo to submit questions, feedback, or propose changes.


<!-- INTRO-END -->
