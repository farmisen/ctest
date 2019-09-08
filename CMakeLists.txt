project(ctest C)

add_library(ctest INTERFACE)

target_include_directories(ctest INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})