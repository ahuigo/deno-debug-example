# deno-debug-example
Bad case reproduce step:
1. Install vscode and vscode-deno plugin.
2. Open this project with vscode
3. Press `F5`, then there will be an error like `error: Uncaught TypeError: WebAssembly.compile(): Argument 0 must be a buffer source`

This is tested by:

    kernel: 21.6.0
    os: macOSX 12.6
    cpu: Darwin 21.6.0 arm64 core(10) Apple M1 Pro
    vscode: 1.76.2 
    deno 1.33.4 
    v8 11.4.183.2
    typescript 5.0.4
    deno extensions: denoland.vscode-deno@3.19.1

