project(learnyoctogitpro C)
cmake_minimum_required(VERSION 2.6.3)

add_executable (learnyoctogit main.c)

install(TARGETS learnyoctogit DESTINATION ${CMAKE_INSTALL_PREFIX}/bin)

