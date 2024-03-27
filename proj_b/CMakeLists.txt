cmake_minimum_required(VERSION 3.17)
target_sources(${PROJECT_NAME} PRIVATE ${PROJECT_NAME}.hpp ${PROJECT_NAME}.cpp)
target_link_options(${PROJECT_NAME} proj_a::static)
add_executable(${PROJECT_NAME})
