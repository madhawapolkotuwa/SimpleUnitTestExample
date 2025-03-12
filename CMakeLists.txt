cmake_minimum_required(VERSION 3.16)
project(try_googletest
        VERSION 0.0.1
        DESCRIPTION "Trying googletest"
        LANGUAGES CXX)

include(cmake/UpdateSubmodules.cmake)

include(CTest)
add_subdirectory(external)
add_subdirectory(project)