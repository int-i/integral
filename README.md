# Integral

![C++](https://img.shields.io/badge/c++-17-00599C?logo=c%2B%2B&logoColor=white&style=for-the-badge)
[![CMake](https://img.shields.io/badge/cmake->=3.14-064F8C?logo=cmake&logoColor=white&style=for-the-badge)](https://cmake.org/)
[![License](https://img.shields.io/github/license/int-i/integral?style=for-the-badge)](./LICENSE)

## Build

### Requirement

- C++17
- CMake(>=3.14)
- [Drogon](https://github.com/an-tao/drogon)(CMake [FetchContent](https://cmake.org/cmake/help/latest/module/FetchContent.html))
  - [JsonCpp](https://github.com/open-source-parsers/jsoncpp)
  - libuuid
  - OpenSSL
  - [TRANTOR](https://github.com/an-tao/trantor)(Git Submodule)
  - zlib

### Guide

1. Clone the repository:

    ```txt
    git clone https://github.com/int-i/integral.git
    ```

2. Build the source:

    ```txt
    cd integral
    cmake -S . -B build
    cmake --build build
    ```

## License

```txt
Copyright 2023 Seungjae Park

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

Integral is licensed under the [Apache License 2.0](./LICENSE).
