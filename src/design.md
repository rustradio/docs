# Design

Rust Radio is first and foremost based on Rust's thriving asynchronous ecosystem. This is not without disadvantages. Many async features in Rust are not stable yet, or have not yet landed in the core library. Thus, some core features still rely on third-party library support.

The project aims to use whatever implementations currently exist, with the prospects that many features will eventually become stable enough to be included natively in core Rust. We hope to assist in expediting that process as best as we can.
