cmake_minimum_required(VERSION 3.9)
project(Example)
find_package(Threads REQUIRED)
add_executable(hello hello.cxx)
