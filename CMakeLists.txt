# SPDX-License-Identifier: MIT

project(linux-serial-test C)
cmake_minimum_required(VERSION 2.6)
add_executable(linux-serial-test linux-serial-test.c)
target_link_libraries(linux-serial-test rt)
install(TARGETS linux-serial-test DESTINATION bin)
