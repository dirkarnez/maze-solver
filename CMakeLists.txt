cmake_minimum_required(VERSION 3.8)

project(maze-solver C)

SET(CMAKE_EXE_LINKER_FLAGS "${CMAKE_EXE_LINKER_FLAGS} -static")

add_executable(${PROJECT_NAME}
    "src/main.c"
)
