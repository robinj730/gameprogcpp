add_executable(ch01 Main.cpp Game.cpp)
target_link_libraries(ch01 PRIVATE PkgConfig::sdl2)