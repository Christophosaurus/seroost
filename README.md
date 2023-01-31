# how to run
download the [OpenGL reference documentation](https://github.com/KhronosGroup/OpenGL-Refpages/tree/main/gl4/html)
html files.

index the documents 
```zsh
cargo run index ./path-to-xml-files
```

then serve them with the index file `index.json`

```zsh
cargo run serve ./index.json
```

go to `127.0.0.1:6969` and run a search like `glsl interpolate linearly`
