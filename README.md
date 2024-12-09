# Unsafe Pointer Manipulation in Rust
This repository demonstrates a potential issue with unsafe pointer manipulation in Rust when working with vectors.  The `bug.rs` file shows incorrect usage, while `bugSolution.rs` provides a safe alternative.

The original code attempts to modify a vector's contents using a raw pointer obtained via `as_mut_ptr()`. This is generally unsafe and can lead to data corruption or memory errors if not done very carefully.  The solution showcases how to safely manipulate vector elements using Rust's safe abstractions.

**Key Concepts:**
* **Unsafe Rust:** Demonstrates how to use unsafe code blocks in Rust and the potential pitfalls.
* **Vector Manipulation:** Explains safe and unsafe ways to modify vector contents.
* **Memory Management:** Highlights the importance of memory safety in Rust.