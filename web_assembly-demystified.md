# WebAssembly Demystified

**Presenter**: Jay Phelps
@_jayphelps

Software Engineer - NETFLIX

# What is WebAssembly (WASM)
* efficient, low-level bytecode for the Web
    * efficient - fast to load and execute
    * low-level bytecode - intended as a compilation target
* runs in a vm; **safe and portable**
    * just like Javascript

**Browsers are already using JIT**

Compiling **JavaScript to WebAssembly** would be all aroud **slower**

* Currently, compiling C/C++ and Rust to WebAssembly

## When should I target WebAssembly?
* Heavily **CPU-bound number computations**
* Games are a good example
    * Funky Carts

* You'll likely consume compiled WebAssembly binaries even sooner

## WebAssembly is a stack machine language
    * data structure with **push** and **pop**
    * LIFO
    * *stack machine*: instructions on a stack


**1 + 2**
```
i32.const 1
i32.const 2
i32.add
```

* Most tooling supports Abstract Syntax Tree **(AST)**
* Source map support is coming soon

## Getting Started
**WebAssembly Explorer** https://mbebenita.github.io/WasmExplorer

# emscripten
*toolchain like clang*
webassembly.org
**You have to compile LLVM from source**

WebPack adding first-class support
    (125$ from MOSS for support)

## What's missing?
* direct access to Web APIs
    * must use javascript
* garbage collection
* multi-threading

## Browser Support
* Every major browser supports it for now
    * android browser included

