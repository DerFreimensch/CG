cmake_minimum_required(VERSION 3.20)
project(CG)

set(CMAKE_CXX_STANDARD 14)

add_executable(CG main.cpp Figure.cpp matrix.cpp Polygon.cpp  window.cpp )

target_link_libraries(CG D:/bgi/SDL_bgi-2.5.0/bin/Mingw64/SDL_bgi.dll)