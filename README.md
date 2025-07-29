# scribere | open source transcription

### Introduction

Scribere is intended to be the one-stop shop for musical transcription. Specifically it's designed to provide the best possible tools for transcription of symphonic works combining AI stem separation techniques, intuitive interface, and acoustic processing to provide the most accurate transcriptions of any file possible.

### Build From Source

Building is based on the CMake system with Unix and tested on MacOS 12.7.4

```bash
git clone https://github.com/Coincadink/scribere.git
cd scribere
git submodule update --init --recursive
mkdir builds
cd builds
cmake ..
make
./scribere
```