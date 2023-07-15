# C++ (Normal Development, Not Competitive Programming)

## Vim vs CLion
I prefer vim (see the vim page) for editing c++ most of the time if I am not doing significant architecting. I use a very normal plugin setup, with `clangd` and `clangformat` as my editors. These are both available through `vim:Mason` which makes life super easy here. All normal plugins apply. 

For big changes, I like CLion a lot. The heftiness of a true IDE helps me when I build completely new stuff without requiring me to build an extensive vim configuration for it - I like to keep my vim configs nice and lightweight. I use it with the WSL toolchain, just so that I can have a Linux environment natively. Obviously I use ideaVim here, but mostly default settings all around. 

### Setup: [CLion](https://www.jetbrains.com/clion/) [vim:Mason](https://github.com/williamboman/mason.nvim)

## Preferred Toolchain

My favorite C++ toolchain right now is CMake + Conan, on C++ 20. C++ 20 is also super nice for competitive programming so this allows me to maintain one real config accross all c++. CMake is just essential, and every package manager has it. Conan takes care of the sketchy dependency management of CMake, and does a great job. It is easier to configure than most other dependency managers, and can be installed with pip which is super easy. 

For unit testing, I am a fan of Google Test and Mock, and have really never seen a reason to swap to something like Catch. For development, I am indifferent on CLang vs GCC, unlike in cp. 

### Setup: CMake (`sudo apt install cmake`), Conan (`pip install Conan`), Build-Essential (`sudo apt install build-essential`), Google Test (`sudo apt install libgtest-dev`), Google Mock (`sudo apt install libgmock-dev`)