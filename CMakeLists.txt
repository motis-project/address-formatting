cmake_minimum_required(VERSION 3.10)
project(address-formatting)

file(GLOB_RECURSE address-formatting-res "${CMAKE_CURRENT_SOURCE_DIR}/conf/*.*")
create_resource("${CMAKE_CURRENT_SOURCE_DIR}/conf/" "${address-formatting-res}" address_formatting_res)
