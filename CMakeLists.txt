cmake_minimum_required(VERSION 3.10)
project(HelloWorld)

add_executable(hello_world main.cpp)

# Enable testing
enable_testing()
add_executable(test_bin tests.cpp)
add_test(NAME MyTest COMMAND test_bin)
