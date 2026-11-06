---
title: "Sovereign Tech Fund Invests in Eclipse 4diac"
date: 2026-11-06T00:00:00-00:00
categories: ["4diac"]
type: "newsitem"
description: |
  Sovereign Tech Fund is investing in Eclipse 4diac! From October 2026 through December 2027, we will tackle a coordinated development effort across the runtime, engineering tools, libraries, and documentation.
fordiacTeamGreating: true
---

### Sovereign Tech Fund Invests in Eclipse 4diac

We have big news: the Sovereign Tech Fund is investing in Eclipse 4diac! From October 2026 through December 2027, we will tackle a coordinated development effort across the runtime, engineering tools, libraries, and documentation.
We are thrilled about this opportunity. Our community has built a substantial foundation over many years. Now we can bring several important developments together and address obstacles to broader industrial adoption. Our ambition is a clear path from the first installation to a working, maintainable automation application—and more possibilities for everyone building with 4diac.
4diac FORTE — Strengthening the Industrial Foundation

Reliable communication and predictable runtime behavior are essential when moving from an engineering project to a real machine. Our work on 4diac FORTE will strengthen that foundation in three areas:
EtherCAT integration: Complete and stabilize the existing integration of the EtherLab EtherCAT Master, supported by benchmarks for cycle timing, synchronization, and determinism. We will also implement and test recovery from bus interruptions.
OPC UA performance: Investigate bottlenecks and optimize memory allocation and data paths. Automated benchmarks will compare memory consumption and throughput against the starting point.
Dynamic type loading: Rework the mechanisms for transferring and executing new function block types, including the corresponding generation and deployment support in 4diac IDE.
Together, these improvements should make industrial integration more practical and allow applications to evolve without rebuilding the entire runtime whenever a new function block type is introduced.
4diac IDE — Making Engineering Easier

Understanding an application, finding a problem, and making a controlled change are everyday engineering tasks. We want 4diac IDE to support these tasks more effectively.
The planned work will improve usability, responsiveness, and state handling, alongside debugging, monitoring, and visualization workflows. The goal is to help you see what your application is doing and move more directly from an observation to its cause.
Behind these workflows, we will improve the separation between user-interface and service logic in selected parts of the tooling. Reproducible build processes and additional automated tests will make changes easier to verify and help preserve improvements as the project develops.
Reusable Libraries — Building on Proven Solutions

A useful building block should be easy to bring into another application—and remain manageable when it changes.
We will extend the existing library infrastructure so that standard libraries can be maintained and released independently of 4diac IDE. The work includes:
A dedicated 4diac-libs repository for independently versioned public function block packages.
GitHub support as an additional library repository provider.
Improved dependency handling and traceable updates between package versions.
Extended refactoring and migration support, backed by automated validation and regression tests.
For application developers, this should make it easier to reuse proven solutions while retaining control over dependencies and updates. For library contributors, it should provide a clearer path to publishing and maintaining packages that others can build on.
From First Steps to Industrial Applications

The capabilities need to come together in an example you can explore yourself. An industrial reference project will demonstrate a realistic control task and reusable building-block patterns.
A test setup with simulated inputs and outputs will allow the reference application to run without physical machinery. Revised documentation and step-by-step tutorials will connect installation, libraries, runtime, and engineering workflows into an end-to-end getting-started path.
Let’s Build the Next Step Together

The results will be developed publicly in the Eclipse 4diac repositories, where they can be reviewed, used, and improved by the community.
Thank you to everyone whose contributions have brought 4diac this far, and to the Sovereign Tech Fund for investing in its continued development. Bring your requirements, test cases, practical experience, and ideas. They will help us turn this opportunity into improvements that matter.
We have a lot ahead of us. We want this work to expand what you can achieve with 4diac—and we cannot wait to build it together!

Moritz Pflaum - MSR Software GmbH