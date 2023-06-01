# docker-nvidia-cuda-ubuntu-memo

## CUDA 11.8
### 11.8.0-cudnn8-devel-ubuntu20.04
基本的にこれを使用する。
[nvidia/cuda:11.8.0-cudnn8-devel-ubuntu20.04](https://hub.docker.com/layers/nvidia/cuda/11.8.0-cudnn8-devel-ubuntu20.04/images/sha256-4382a0abe459a38838794ef1356c7be7ed2d0f74e6fd4fb7e3d7a0f6c6919aa0)
```bash
docker pull nvidia/cuda:11.8.0-cudnn8-devel-ubuntu20.04
```
### 11.8.0-cudnn8-runtime-ubuntu20.04
[nvidia/cuda:11.8.0-cudnn8-runtime-ubuntu20.04](https://hub.docker.com/layers/nvidia/cuda/11.8.0-cudnn8-runtime-ubuntu20.04/images/sha256-60722cdda861cade808a62460d41958425065d81bdb88f9cea0e91d018cb182e)
```bash
docker pull nvidia/cuda:11.8.0-cudnn8-runtime-ubuntu20.04
```
### 11.8.0-devel-ubuntu20.04
[nvidia/cuda:11.8.0-devel-ubuntu20.04](https://hub.docker.com/layers/nvidia/cuda/11.8.0-devel-ubuntu20.04/images/sha256-6e12af425102e25d3e644ed353072eca3aa8c5f11dd79fa8e986664f9e62b37a)
```bash
docker pull nvidia/cuda:11.8.0-devel-ubuntu20.04
```
### 11.8.0-runtime-ubuntu20.04
[nvidia/cuda:11.8.0-runtime-ubuntu20.04](https://hub.docker.com/layers/nvidia/cuda/11.8.0-runtime-ubuntu20.04/images/sha256-872f03ad4329a99c7c9812657c6ee1a867d779a9887af93ae810a7bfa45d69ca)
```bash
docker pull nvidia/cuda:11.8.0-runtime-ubuntu20.04
```
### 11.8.0-base-ubuntu20.04
[nvidia/cuda:11.8.0-base-ubuntu20.04](https://hub.docker.com/layers/nvidia/cuda/11.8.0-base-ubuntu20.04/images/sha256-436324fa946943e170fb246d8e911241c0b93bd5fb6256a964a7d01b06dfcf68)
```bash
docker pull nvidia/cuda:11.8.0-base-ubuntu20.04
```

## 参考
https://qiita.com/k_ikasumipowder/items/32bf0bc781cbbdfa2edb
- base: 最小構成

- runtime: baseを拡張したもの

- devel: runtimeを拡張したもの

開発用・学習用であれば、基本的にdevelを選んでおけば問題ないと思います。(devel にしか　nvccが無いなどの問題がある)
