cmake_minimum_required(VERSION 3.0)
project(cup)

add_executable(${PROJECT_NAME} teamwork/main.cpp)

target_compile_features(${PROJECT_NAME} PRIVATE cxx_std_17)

target_link_libraries(${PROJECT_NAME} PRIVATE sfml-system sfml-window sfml-graphics sfml-audio sfml-network)
