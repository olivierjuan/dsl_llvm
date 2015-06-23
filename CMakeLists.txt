cmake_minimum_required(VERSION 3.1)

Project(dsl_llvm)

Find_Package(Boost)

include_directories(${Boost_INCLUDE_DIR})
add_executable(dsl src/main.cpp)
