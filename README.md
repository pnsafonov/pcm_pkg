# Intel PCM packages

Use **Releases** to download package.

## Build

```bash
git clone https://github.com/intel/pcm.git
cd pcm
git checkout 202405
git submodule update --init --recursive

mkdir build
cd build
cmake ..
cmake --build . --parallel
cpack
```