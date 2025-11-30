cmake_minimum_required(VERSION 3.5)
project(cutefish-cursor)

install(DIRECTORY cutefish-dark DESTINATION ${CMAKE_INSTALL_PREFIX}/share/icons)
install(DIRECTORY cutefish-light DESTINATION ${CMAKE_INSTALL_PREFIX}/share/icons)
