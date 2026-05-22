cmake_minimum_required(VERSION 3.14)
project(cmd)

add_executable(fst main.cc)

target_include_directories(fst PRIVATE ..)
target_link_libraries(fst PRIVATE pcre2-8)