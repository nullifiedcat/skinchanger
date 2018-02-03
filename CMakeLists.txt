cmake_minimum_required(VERSION 3.3)
project(catiface CXX)

set(CMAKE_CXX_FLAGS "-std=c++17")

file(GLOB_RECURSE SOURCES "src/*.cpp") 

add_executable(skinchanger ${SOURCES})
target_link_libraries(skinchanger -lpthread -lstdc++fs)
set_target_properties(skinchanger PROPERTIES COMPILE_FLAGS "-m32" LINK_FLAGS "-m32")

include_directories(include) 