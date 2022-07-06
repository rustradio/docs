# Background

Rust Radio is a modern signal processing framework. It aims to leverage the powerful ecosystem that the Rust community has built to allow users to easily implement highly-performant signal processing flows.

## Alternatives

Many other frameworks and tools that exist today allow users to implement very complicated signal processing flows. These tools have served the authors very well throughout the years. However, each framework has its pros and cons. In this section we will review how Rust Radio differs from the existing tools available.

### GNU Radio

No doubt the most comprehensive toolkit for signal processing is [GNU Radio](https://www.gnuradio.org/). It has existed for a very long time and has garnered a thriving ecosystem.

While GNU Radio is built on very strong technical foundations and offers unparalleled performance, it comes at a price of high complexity both in the codebase as well as in runtime. While GNU Radio flows strive to be embeddable and allow for easy integration with out-of-tree modules, in practice it falls short and runs into various runtime complexities.

### LuaRadio

[LuaRadio](https://luaradio.io/) is a lightweight framework implemented in the Lua scripting language, which offers a very friendly API. Many of Rust Radio's features have been inspired by how LuaRadio does things. However, since Rust Radio compiles down natively to the various supported platforms, this allows for better integration opportunities with other system libraries and tools as opposed to a JIT-interpreted framework.
