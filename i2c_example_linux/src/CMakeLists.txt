cmake_minimum_required(VERSION 3.0)

project(I2C_userspace)

add_executable(${PROJECT_NAME} main.c i2c.c i2c.h)


