cmake_minimum_required(VERSION 3.16)
project(JobAnsi
    VERSION 0.0.1
    LANGUAGES CXX
)

add_subdirectory(libs)
enable_testing()
add_subdirectory(tests)
