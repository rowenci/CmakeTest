cmake_minimum_required(VERSION 3.23)
project(cmakeTest)

set(CMAKE_CXX_STANDARD 17)

ADD_SUBDIRECTORY(hello helloBin)
ADD_SUBDIRECTORY(world worldBin)
ADD_SUBDIRECTORY(lib libBin)
