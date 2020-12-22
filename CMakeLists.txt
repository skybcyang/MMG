cmake_minimum_required(VERSION 3.17)
project(mmg)

set(CMAKE_CXX_STANDARD 17)

add_executable(mmg
        one_dimensional/1d_map_generator.h
        two_dimensional/2d_map_generator.h
        three_dimensional/3d_map_generator.h
        multi_dimensional/md_map_generator.h
        third_party/catch.hpp
        test/test_.cpp catch.cpp)