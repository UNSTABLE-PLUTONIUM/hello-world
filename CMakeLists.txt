cmake_minimum_required(VERSION 3.15)

project(hello-world)

add_executable(hello ./src/hello.c)

target_compile_options(hello PRIVATE "--std=c99")
