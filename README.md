# WebAssembly in Rocq

Existing WebAssembly formalizations in various proof assistants do not take advantage of SpecTec, a new domain-specific language which is now used in the WebAssembly specification. The goal of this project is to automatically translate SpecTec code into Rocq and to maintain proofs of various properties about the WebAssembly language as the official specification evolves.

It is my belief that WebAssembly serves as a solid base to build verified programs. This project will evolve into a program verification framework based on WebAssembly. This is not just a project to verify the correctness of the WebAssembly specification.

## Why Rocq and not other proof assistants?

Personal preference. There is no technical reason. It's the proof assistant that I'm most familiar with.

It is my hope that users of other proof assistants can use this as a blueprint to implement similar projects in their respective communities.
