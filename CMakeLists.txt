cmake_minimum_required(VERSION 3.3)
project(ipd15a CXX)
include(.ipd/cmake/CMakeLists.txt)

add_cxx_test_program(deque_test
        test/deque_test.cxx)
