cmake_minimum_required(VERSION 3.10)
project(GemmCompute)

set(srcs ./src/common.cpp
         ./src/main.cpp
         ./src/optimize/gemm_ref.cpp)

add_executable(${PROJECT_NAME} ${srcs})