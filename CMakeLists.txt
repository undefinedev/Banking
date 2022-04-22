cmake_minimum_required(VERSION 3.18)

set(CMAKE_CXX_STANDARD 20)

project(bank)

add_library(account STATIC Account.cpp Account.h)
add_library(transaction STATIC Transaction.cpp Transaction.h)
