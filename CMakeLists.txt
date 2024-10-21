cmake_minimum_required(VERSION 3.27)
project(ESTF___Mission_MARC C)

set(CMAKE_C_STANDARD 11)

add_executable(ESTF___Mission_MARC main.c
        loc.c
        loc.h
        moves.c
        moves.h
        map.c
        map.h
        queue.c
        queue.h
        stack.c
        stack.h)
