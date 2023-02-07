cmake_minimum_required(VERSION 3.14)
project(Integral
        VERSION 1.0.0
        DESCRIPTION "<int i> Member Management Service"
        HOMEPAGE_URL https://github.com/int-i/integral
        LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

include(FetchContent)
FetchContent_Declare(
    drogon
    GIT_REPOSITORY https://github.com/drogonframework/drogon.git
    GIT_TAG        v1.8.3
)
FetchContent_MakeAvailable(drogon)

add_subdirectory(src)
