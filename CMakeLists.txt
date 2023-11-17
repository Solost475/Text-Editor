cmake_minimum_required(VERSION 3.0)

project("TEXT EDITOR" C)
#设置C标准为C99
# set(CMAKE_C_STANDARD 99)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra -pedantic -std=c99")

add_executable(kilo kilo.c)

# target_compile_options(kilo PRIVATE -Wall -Wextra -pedantic)