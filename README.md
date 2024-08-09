# standards-positions
The Node.js Projects Official Positions on various standards proposals

To be filled out soon. This repository will contain the official positions of the Node.js project towards various standards proposals that potentially impact the runtime. Please stay tuned for updates.

Refs: https://github.com/nodejs/admin/issues/841

## Introduction

This repository serves much the same purpose as Mozilla's standards positions repository seen here: https://github.com/mozilla/standards-positions ... that is, it effectively serves as the repository for the Node.js project's official thoughts for various specifications relevant to Node.js.

Background
Node.js implements support for multiple internet and web standards (TCP, HTTP, TLS, WHATWG URL, Streams, Encoding, fetch, etc). Historically, the Node.js project has never maintained any official position favorable or unfavorable towards any particular specification. Instead it has relied mostly on the individual opinions and perspectives of individual contributors. Some of these individual contributors have participated in various standards bodies such as TC-39 or WHATWG representing their own personal points of view. That participation, however, often becomes confusing when it is not clear if they are speaking on behalf of the project representing a consensus opinion among the contributors or merely their own individual opinions. This repository seeks to eliminate that confusion by providing an authoritative source for consensus agreements.

## Process

We will apply one of several possible labels to new specifications:

* “asking for modification”
* “no concerns so far”
* “strong concerns” (and if possible, list of concerns)
* “integration/implementation planned”
* “integration/implementation in progress”

These positions will be based on our best assessment of the current state of the specification and the potential for it to benefit our users and the ecosystem as a whole. We consider the intended purpose and the design fundamentals of each specification. Incomplete documentation, minor issues, or lack of interoperability testing are not reasons for a negative position, provided that intent is clear.

We might also use the following labels for specifications where we have not formed a position:

* defer - Node.js takes no position on this work.
* under consideration - Node.js has not taken a position on this work and is gathering more information.

An already published position that, for whatever reason, becomes no longer relevant can be marked obsolete.

A proposal to publish an opinion towards a particular specification would come in the form of a new issue in the nodejs/standards-position repository. The issue should identify the spec and the rationale for seeking a position. ***It should not argue a particular position label*** one way or the other but simply ask that the spec be considered. If there are no objections raised to the proposal after seven calendar days, then the proposal is considered accepted and work can start to publish a position.

Each position itself would be published as a separate markdown file in the repository, originating with a pull request whose process for acceptance follows the same process as landing semver-major changes in the core Node.js repository. That is, a position paper cannot land without approval from at least two TSC members and without all relevant feedback having been addressed. Collaborators will be encouraged to follow the repository and actively weigh in where they feel necessary.

Positions are living documents that can be revisited and altered as necessary when new information is received or project requirements evolve. We will use the git history to track any changes in position over time.

## Template for proposals

```
<!-- Please use only the specification title as the issue title. -->

## Request for Node.js Position on an Emerging Specification

* Specification title:
* Specification or proposal URL (if available):
* Explainer URL (if available):
* Proposal author(s) (`@`-mention GitHub accounts):
* Node.js collaborators or ecosystem members who can provide input (optional)

### Notes

Notes about the spec and why it should be considered. Again, please no arguing for a specific position, just details that would be helpful in determining relevancy
```
