cmake_minimum_required(VERSION 3.5)
project(snap-test-exec)
set(CMAKE_CXX_STANDARD 17)
add_executable(${PROJECT_NAME} main.cpp)
install(TARGETS ${PROJECT_NAME}
        RUNTIME DESTINATION bin)
