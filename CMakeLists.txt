cmake_minimum_required(VERSION 3.10)
project(osua VERSION 1.0 LANGUAGES C)

add_executable(osua_executable main.c kernel/boot.c kernel/kernel.c)

