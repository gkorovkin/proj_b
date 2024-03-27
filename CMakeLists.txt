cmake_minimum_required(VERSION 3.17)

set(CMAKE_DISABLE_SOURCE_CHANGES ON)
set(CMAKE_DISABLE_IN_SOURCE_BUILD ON)

project(proj_b)

FetchContent_Declare(proj_a
	GIT_REPOSITORY git@github.com:gkorovkin/proj_a.git
	GIT_PROGRESS ON
)

add_subdirectory(${PROJECT_NAME})
