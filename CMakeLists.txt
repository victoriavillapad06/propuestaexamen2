cmake_minimum_required(VERSION 3.29)
project(propuestaexamen2)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(funciones)

add_executable(propuestaexamen2
    funciones/funciones.cpp
    funciones/funciones.h
    main.cpp
)
