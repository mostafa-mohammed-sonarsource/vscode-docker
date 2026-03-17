# C++17 Hello World in Ubuntu 24 Dev Container

## Prerequisites
- Docker Desktop (running)
- VS Code
- VS Code extension: `Dev Containers` (`ms-vscode-remote.remote-containers`)

## Open in Container
1. Open this folder in VS Code.
2. Run `Dev Containers: Reopen in Container` from the command palette.
3. Wait for the image build to finish.

## Build and Run
Inside the VS Code terminal (which is now in Ubuntu 24.04):

```bash
cmake -S . -B build -G Ninja
cmake --build build
./build/hello_world
```

Expected output:

```text
Hello, World!
```
