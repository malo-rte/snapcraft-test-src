cmake_minimum_required(VERSION 3.5)
project(snap-test-exec)
add_executable(${PROJECT_NAME} main.cpp)
install(TARGETS ${PROJECT_NAME}
        RUNTIME DESTINATION bin)
