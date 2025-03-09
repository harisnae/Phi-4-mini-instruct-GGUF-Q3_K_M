# Phi-4-mini-instruct-GGUF-Q3_K_M

This is a 3-bit quantized [GGUF](https://github.com/ggml-org/ggml/blob/master/docs/gguf.md) of Microsoft's [Phi-4-mini-instruct](https://github.com/marketplace/models/azureml/Phi-4-mini-instruct) 3.8B parameters Small Language Model.

## Description

The weights are quantized with [llama.cpp](https://github.com/ggml-org/llama.cpp) to a 3-bit quantization (Q3_K_M). The [Screen capture](https://github.com/harisnae/Phi-4-mini-instruct-GGUF-Q3_K_M/blob/main/SCREENSHOT-Phi-4-mini-instruct-GGUF-Q3_K_M_interactive_mode.png) shows the simple CLI interface of this quantized SML, which runs in Linux Terminal locally on a computer with Intel CORE i5 CPU **without internet**.

## Getting Started

### Dependencies

* [Debian](https://www.debian.org/distrib/) or [Ubuntu](https://ubuntu.com/download)
* [Python](https://github.com/python/cpython)
* [Python Virtual Environment](https://github.com/pypa/virtualenv)
* [llama.cpp - LLM inference in C/C++ ](https://github.com/ggml-org/llama.cpp)

### Installation

* [Guide to the installation of llama.cpp, quantization and use of LM](https://github.com/SteelPh0enix/steelph0enix.github.io/blob/master/content/posts/llama-cpp-guide.md)

### Executing program

* Simply download the "Phi-4-mini-instruct-GGUF-Q3_K_M.gguf" file or clone the repository
```
git clone https://github.com/harisnae/Phi-4-mini-instruct-GGUF-Q3_K_M
```
* To run this Language Model in a simple CLI interface, provide the directory path to "llama-cli" and "Phi-4-mini-instruct-GGUF-Q3_K_M.gguf" in the Terminal.
```
(Path to llama CLI)/llama.cpp/build/bin/llama-cli --color --conversation --model (Path to model GGUF file)/Phi-4-mini-instruct-GGUF-Q3_K_M.gguf
```

## Author

[Haris Naeem ](https://github.com/harisnae)

## Version History

* 0.1
    * Initial Release

## License

This project is licensed under the MIT License - see the [LICENSE.md](/LICENSE.md) file for details

## Acknowledgments

* [Phi-4-mini-instruct](https://huggingface.co/microsoft/Phi-4-mini-instruct)
* [GGUF](https://github.com/ggml-org/ggml/blob/master/docs/gguf.md)
* [llama-cpp-guide](https://github.com/SteelPh0enix/steelph0enix.github.io/blob/master/content/posts/llama-cpp-guide.md)
* [README template](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)

## Screenshot

![Phi-4-mini-instruct-GGUF-Q3_K_M](/SCREENSHOT-Phi-4-mini-instruct-GGUF-Q3_K_M_interactive_mode.png?raw=true)
