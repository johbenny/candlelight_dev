cmake_minimum_required(VERSION 3.16)

include_directories(header)
aux_source_directory(source SRC_LIST)

add_executable(main ${SRC_LIST})