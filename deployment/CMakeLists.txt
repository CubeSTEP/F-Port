cmake_minimum_required(VERSION 3.15)
project(BryanFprime)

add_subdirectory(${CMAKE_CURRENT_LIST_DIR}/../F-Prime ${CMAKE_CURRENT_BINARY_DIR}/F-Prime)
add_subdirectory(${CMAKE_CURRENT_LIST_DIR}/../targets/stm32h7 ${CMAKE_CURRENT_BINARY_DIR}/targets/stm32h7)
