cmake_minimum_required (VERSION 3.19)

project (project_name)

add_subdirectory(pybind11)

pybind11_add_module(simple_python src/simple_binding.cpp)
