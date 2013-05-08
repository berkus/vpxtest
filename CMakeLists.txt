cmake_minimum_required(VERSION 2.8)

add_executable(vpxtest my_vpx_test.c)
find_library(LIBVPX vpx)
target_link_libraries(vpxtest ${LIBVPX})
