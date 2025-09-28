cmake_minimum_required(VERSION 3.28)

project(o1heap)

add_library(${PROJECT_NAME} STATIC
    "o1heap/o1heap.c"
)

target_include_directories(${PROJECT_NAME}
    PUBLIC
        "o1heap"
)
