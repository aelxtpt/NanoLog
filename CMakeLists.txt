cmake_minimum_required(VERSION 3.10)

project(nanolog LANGUAGES C CXX ASM)

set(CMAKE_CXX_STANDARD 20)

file(GLOB_RECURSE
    SOURCE_FILES
    ${PROJECT_SOURCE_DIR}/source/*.cc)

add_library(nanolog ${SOURCE_FILES})