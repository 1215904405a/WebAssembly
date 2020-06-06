# WebAssembly
WebAssembly mac 安装

参考：https://webassembly.org/getting-started/developers-guide/

git clone https://github.com/emscripten-core/emsdk.git

cd emsdk

./emsdk install latest

./emsdk activate latest

source ./emsdk_env.sh --build=Release

emcc 能执行 安装成功


