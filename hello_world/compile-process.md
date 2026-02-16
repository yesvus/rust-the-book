## Cargo Commands

### `cargo build`
Compiles the project and generates executables in the `target/` directory.

### `cargo run`
Compiles (if necessary) and runs the executable. Automatically builds before running if not already compiled.

### `cargo check`
Validates code for errors without producing a binary. Significantly faster than `cargo build`.

### `cargo build --release`
This will make the compiling time longer, but it will be more optimized. This is intended for production, not development.