cmake_minimum_required(VERSION 3.28)
project(GLuck)

set(CMAKE_CXX_STANDARD 20)

find_package(glfw3 REQUIRED)
find_package(OpenGL REQUIRED)

add_executable(GLuck src/main.cpp src/glad.c)
target_include_directories(GLuck PRIVATE
        ${CMAKE_CURRENT_SOURCE_DIR}/include
)
target_link_libraries(GLuck PRIVATE glfw OpenGL::GL)

