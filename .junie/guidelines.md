# llama.cpp Project Overview

## Introduction
llama.cpp is a C/C++ implementation for inference of LLaMA and other large language models (LLMs). The project enables LLM inference with minimal setup and state-of-the-art performance on a wide range of hardware - locally and in the cloud.

## Key Features
- Plain C/C++ implementation without any dependencies
- Apple silicon is a first-class citizen - optimized via ARM NEON, Accelerate and Metal frameworks
- AVX, AVX2, AVX512 and AMX support for x86 architectures
- Multiple quantization options (1.5-bit to 8-bit) for faster inference and reduced memory use
- Custom CUDA kernels for NVIDIA GPUs, with support for AMD GPUs via HIP and Moore Threads MTT GPUs via MUSA
- Vulkan and SYCL backend support
- CPU+GPU hybrid inference for models larger than VRAM capacity

## Supported Models
The project supports a wide range of models including:
- LLaMA, LLaMA 2, and LLaMA 3
- Mistral 7B and Mixtral MoE
- DBRX
- Falcon
- Chinese LLaMA/Alpaca
- Many other models and their fine-tunes

## Project Goals
The main goal of llama.cpp is to democratize access to LLMs by providing:
1. Efficient inference capabilities on consumer hardware
2. Minimal dependencies for easy setup and deployment
3. State-of-the-art performance optimizations
4. Support for a wide range of hardware configurations

## Development
The llama.cpp project serves as the main playground for developing new features for the ggml library. Contributors are welcome to participate in the project's development by following the guidelines in the CONTRIBUTING.md file.

## Resources
- [GitHub Repository](https://github.com/ggml-org/llama.cpp)
- [Documentation](https://github.com/ggml-org/llama.cpp/tree/master/docs)
- [Examples](https://github.com/ggml-org/llama.cpp/tree/master/examples)
- [Roadmap](https://github.com/users/ggerganov/projects/7)
- [Project Status](https://github.com/ggml-org/llama.cpp/discussions/3471)
