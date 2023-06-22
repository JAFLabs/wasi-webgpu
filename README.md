# WASI WebGPU

A proposed [WebAssembly System Interface](https://github.com/WebAssembly/WASI) API for [WebGPU](https://www.w3.org/TR/webgpu/).

### Current Phase

`wasi-webgpu` is currently in [Phase 0].

[Phase 0]: https://github.com/WebAssembly/WASI/blob/main/Proposals.md#phase-0---pre-proposal-cg


### Champions

- Calvin Prewitt

### Phase 4 Advancement Criteria

TODO before entering Phase 2.

### Introduction

`wasi-webgpu` is a [World] proposal for environments that support the W3C [WebGPU](https://www.w3.org/TR/webgpu/) specification, which exposes an API for performing operations on a Graphics Processing Unit (GPU).

[World]: https://github.com/WebAssembly/component-model/blob/main/design/mvp/WIT.md#wit-worlds

### Goals

`wasi-webgpu` aims to be useful for:

 - GPU-accelerated operations that execute in web browsers, mobile devices, and server environments;
 - Executing computation for small and large AI models;
 - Performing rendering operations;

### Non-goals

`wasi-webgpu` is not aiming to reinvent the [WebGPU](https://www.w3.org/TR/webgpu/) specification and should maintain compatibility with the W3C proposal.

### API walk-through

The full API documentation can be found in the [wit subdirectory](wit).

#### [Use case 1]

[Provide example code snippets and diagrams explaining how the API would be used to solve the given problem]

#### [Use case 2]

[etc.]

### Detailed design discussion

[This section should mostly refer to the .wit.md file that specifies the API. This section is for any discussion of the choices made in the API which don't make sense to document in the spec file itself.]

#### [Tricky design choice #1]

[Talk through the tradeoffs in coming to the specific design point you want to make.]

```
// Illustrated with example code.
```

[This may be an open question, in which case you should link to any active discussion threads.]

#### [Tricky design choice 2]

[etc.]

### Considered alternatives

[This section is not required if you already covered considered alternatives in the design discussion above.]

#### [Alternative 1]

[Describe an alternative which was considered, and why you decided against it.]

#### [Alternative 2]

[etc.]

### Stakeholder Interest & Feedback

TODO before entering Phase 3.

[This should include a list of implementers who have expressed interest in implementing the proposal]

### References & acknowledgements

Many thanks for valuable feedback and advice from:

- [Person 1]
- [Person 2]
- [etc.]
