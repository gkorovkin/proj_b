cmake_minimum_required(VERSION 3.17)
add_executable(${PROJECT_NAME})
target_sources(${PROJECT_NAME} PRIVATE ${PROJECT_NAME}.hpp ${PROJECT_NAME}.cpp)
target_link_options(${PROJECT_NAME} PRIVATE proj_a::static)
