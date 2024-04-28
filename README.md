# Zerops x Yew


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
 

