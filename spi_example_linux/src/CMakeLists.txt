cmake_minimum_required(VERSION 3.0)
project(spi-userspace)

add_executable(${PROJECT_NAME} main.c spi.c spi.h)
