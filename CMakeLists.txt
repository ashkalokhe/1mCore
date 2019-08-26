cmake_minimum_required(VERSION 2.8)
project(1mCore)

option(BUILD_PXCORE "BUILD_WITH_DSPFILTERS" ON)
option(BUILD_PXSCENE "BUILD_1MCORE" ON)

if (BUILD_1MCORE)
    message("Building 1mCore")
    add_subdirectory(src/)
endif (BUILD_1MCORE)
