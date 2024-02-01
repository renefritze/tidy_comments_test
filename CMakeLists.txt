cmake_minimum_required(VERSION 3.10)
project("comments test" CXX)

add_executable(comments_test comments_test.cpp)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON CACHE INTERNAL "" FORCE)
