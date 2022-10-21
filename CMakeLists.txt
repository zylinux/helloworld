project(learnyocto C)
cmake_minimum_required(VERSION 2.6.3)

add_executable (learnyocto main.c)

install(TARGETS learnyocto DESTINATION ${CMAKE_INSTALL_PREFIX}/bin)

