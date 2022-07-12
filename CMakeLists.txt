cmake_minimum_required(VERSION 3.10)
project (raygui)
set (CMAKE_CXX_STANDARD 17)

add_library (raygui INTERFACE)
target_include_directories (raygui INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)

