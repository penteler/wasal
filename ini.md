shell commands
```after installing rust
cargo new --lib fir-wse
```
```after insalling wasm-pack
PS C:\Users\shivani\sv\wasal\fir-wse> wasm-pack build --target web
[INFO]: 🎯  Checking for the Wasm target...
info: downloading component 'rust-std' for 'wasm32-unknown-unknown'
info: installing component 'rust-std' for 'wasm32-unknown-unknown'
 17.4 MiB /  17.4 MiB (100 %)   5.4 MiB/s in  3s ETA:  0s
[INFO]: 🌀  Compiling to Wasm...
   Compiling proc-macro2 v1.0.79
   Compiling unicode-ident v1.0.12
   Compiling wasm-bindgen-shared v0.2.92
   Compiling log v0.4.21
   Compiling bumpalo v3.15.4
   Compiling once_cell v1.19.0
   Compiling wasm-bindgen v0.2.92                                                       
   Compiling cfg-if v1.0.0                                                              
   Compiling quote v1.0.35                                                              
   Compiling syn v2.0.58
   Compiling wasm-bindgen-backend v0.2.92
   Compiling wasm-bindgen-macro-support v0.2.92
   Compiling wasm-bindgen-macro v0.2.92                                                 
   Compiling fir-wse v0.1.0 (C:\Users\shivani\sv\wasal\fir-wse)
error: expected one of `!` or `[`, found `wasm_bindgen`
 --> src\lib.rs:3:2
  |
3 | #wasm_bindgen
  |  ^^^^^^^^^^^^ expected one of `!` or `[`

error: could not compile `fir-wse` (lib) due to 1 previous error
Error: Compiling your crate to WebAssembly failed
Caused by: Compiling your crate to WebAssembly failed
Caused by: failed to execute `cargo build`: exited with exit code: 101
  full command: "cargo" "build" "--lib" "--release" "--target" "wasm32-unknown-unknown" 
```  
```after error
PS C:\Users\shivani\sv\wasal\fir-wse> wasm-pack build --target web
[INFO]: 🎯  Checking for the Wasm target...
[INFO]: 🌀  Compiling to Wasm...
   Compiling fir-wse v0.1.0 (C:\Users\shivani\sv\wasal\fir-wse)
    Finished release [optimized] target(s) in 2.66s
[INFO]: ⬇️  Installing wasm-bindgen...
[INFO]: Optimizing wasm binaries with `wasm-opt`...
[INFO]: Optional fields missing from Cargo.toml: 'description', 'repository', and 'license'. These are not necessary, but recommended
[INFO]: ✨   Done in 33.67s
[INFO]: 📦   Your wasm pkg is ready to publish at C:\Users\shivani\sv\wasal\fir-wse\pkg.
PS C:\Users\shivani\sv\wasal\fir-wse> cd..
PS C:\Users\shivani\sv\wasal> vim ini.md
PS C:\Users\shivani\sv\wasal> 
```
