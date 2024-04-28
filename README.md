# Zerops x Yew

A yew example for Zerops that you can deploy in 2 steps on zerops. Deploy multi-threaded front-end web apps with WebAssembly.

Features

- Yew
- Trunk

Navigate to the Zerops Dashboard and locate the import project button on the sidebar.

Paste the Project Yaml

```yaml
project:
  name: rust

services:
  - hostname: yew
    type: rust@1
    buildFromGit: https://github.com/fxck/zerops-yew
    ports:
      - port: 8080
        httpSupport: true
    enableSubdomainAccess: true
    minContainers: 1
```
