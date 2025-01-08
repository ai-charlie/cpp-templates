# 指定CMake最低版本要求
cmake_minimum_required(VERSION 3.10)

# 设置项目名称
project(CMakeProject)

# 设置C++标准
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# 添加可执行文件
add_executable(MyExecutable src/test.cc)