cmake_minimum_required(VERSION 3.10)

project(banking)


set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)


add_library(banking STATIC Account.cpp Transaction.cpp)
