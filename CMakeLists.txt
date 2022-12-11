cmake_minimum_required(VERSION 3.0)
project(bin_autopatcher)

# main target
add_executable(bin_autopatcher)
target_sources(bin_autopatcher PRIVATE src/patcher.cpp)
set_property(TARGET bin_autopatcher PROPERTY CXX_STANDARD 20)
