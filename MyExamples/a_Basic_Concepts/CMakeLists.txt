cmake_minimum_required(VERSION 3.13)
project(a_Basic_Concepts)

set(SOURCES
	main.cpp)

add_executable(a_Basic_Concepts
	${SOURCES})

target_link_libraries(
	${PROJECT_NAME}
	PUBLIC
		vcglib
	)
