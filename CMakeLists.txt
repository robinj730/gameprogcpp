cmake_minimum_required(VERSION 3.10)
project(gameprogcpp)

find_package(PkgConfig REQUIRED)
pkg_check_modules(sdl2 REQUIRED IMPORTED_TARGET
    sdl2
    SDL2_image
)

add_subdirectory(Chapter01)
