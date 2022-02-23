cmake_minimum_required(VERSION 3.2)

include("cmake/HunterGate.cmake")
HunterGate(
    URL "https://github.com/cpp-pm/hunter/archive/b626a6158599ed58db9e02763d2a815adbae5478.tar.gz"
    SHA1 b3be07c82d4fdadb2ebb81c235a007758a970444
)

# Project
project(protobuf C CXX)

hunter_add_package(ZLIB)

add_subdirectory(cmake)
