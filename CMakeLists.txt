cmake_minimum_required(VERSION 3.5) # CI is atm on 3.5, my dev machine on 3.9
project(tmva-branch-adder-user VERSION 0.1)
#find_package(tmva-branch-adder 0.5 REQUIRED)
find_package(tmva-branch-adder REQUIRED)
add_executable(main main.cpp)
target_link_libraries(main BranchAdder)
