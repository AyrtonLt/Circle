cmake_minimum_required(VERSION 3.23)
project(Circle)

set(CMAKE_CXX_STANDARD 14)

add_executable(Circle main.cpp)

target_link_libraries(Circle ${OPENGL_LIBRARIES})
target_link_libraries(Circle ${GLUT_LIBRARIES})
target_link_libraries(Circle -lopengl32 -g -lfreeglut)