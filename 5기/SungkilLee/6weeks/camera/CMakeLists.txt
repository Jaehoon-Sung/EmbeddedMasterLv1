cmake_minimum_required(VERSION 3.0)

project(camera C)
set(CMAKE_C_STANDARD 99)
set(SOURCE main/main.c main/select_function.c
        protocol/protocol_handler.c
        receiver/receiver.c)

add_executable(${PROJECT_NAME} ${SOURCE})