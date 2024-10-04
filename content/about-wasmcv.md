+++
title = "About wasmCV"
+++

wasmCV provides WebAssembly guest interface bindings for computer vision applications based on [OpenCV](https://github.com/opencv/opencv).

It includes [WIT](https://github.com/WebAssembly/component-model/blob/main/design/mvp/WIT.md) files defining the interface to be used between a WebAssembly host application and a WASM guest module intended to process OpenCV `Mat` image frames.

These interface definitions are then used to generate WASM bindings for TinyGo, Rust, and C. Those bindings can then be used in a WASM guest module to call OpenCV functions implemented by the host to obtain information or perform operations on OpenCV image frames.

The repository for wasmCV is located at https://github.com/wasmvision/wasmcv

Go bindings are located at https://github.com/wasmvision/go-wasmcv

Rust crate is located at https://crates.io/crates/wasmcv

C language files are located at https://github.com/wasmvision/wasmcv/tree/main/components/c/wasmcv
