# wasm-template
This is a template for my coding Projects written in WebAssembly.

## Important commands
Compile WASM file
/dir/emsdk
em++ -I. -o ../../main.js -Oz -s MODULARIZE=1 -s EXPORT_NAME=createModule --bind ../../src/main.cpp ../../src/bindings.cpp

Run files on local server
/
python -m http.server