# warg

`warg` is an in-development open source registry protocol for [Wasm](https://webassembly.org/) packages. `warg` provides an index allowing everyone to refer to federated namespaces of Wasm packages without being opinionated about how package content is stored and hosted.

Check out our Cloud Native Wasm Day talk [slides](https://static.sched.com/hosted_files/cloudnativewasmdayna22/46/Wasm%20Day%20-%20SIG-Registry%20Talk.pdf) and the recording on [YouTube](https://www.youtube.com/watch?v=niCLN2NMZQs)!

## What's a package?

A package is either Wasm code (e.g. components) or an interface descriptor (e.g. worlds).

## Principles

`warg` is...
* [Component Model](https://github.com/webAssembly/component-model) oriented
  * `warg` will give canonical names and versions to Wasm packages.
* Federated & highly inter-operable
  * `warg` will allow independent registries to control their own namespaces and refer to each other.
* Content storage & delivery agnostic
  * `warg` doesn't have an opinion on where & how your package content is stored.
* Advancing supply chain security
  * `warg` offers "Package Transparency" inspired by Certificate Transparency technology to enhance supply chain security.

## Get Involved

Please join us in making `warg` a reality!!

### Bytecode Alliance Registries SIG

`warg` is a Bytecode Alliance project within the [Registries SIG](). Instructions for joining the meetings and reading our minutes can be found [here](https://github.com/bytecodealliance/meetings/tree/main/sig-registries).

### Zulip

`warg` has a stream on the Bytecode Alliance Zulip that you can find [here](https://bytecodealliance.zulipchat.com/#narrow/stream/352111-warg).

### Repos

Code and specifications are a work-in-progress, please attend our meetings before filing any significant issues/PRs.

* [Registry Design and Specification](https://github.com/bytecodealliance/SIG-Registries/)
  * [`warg` Proposal](https://github.com/bytecodealliance/SIG-Registries/pull/25)
* [Registry Prototypes & Reference Implementation](https://github.com/bytecodealliance/registry)
