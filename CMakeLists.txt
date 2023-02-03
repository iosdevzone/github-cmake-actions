cmake_minimum_required(VERSION 3.24)
project (github-cmake-actions)

add_executable(gmake-cmake-actions "")
target_sources(gmake-cmake-actions
	PRIVATE
		src/main.cpp
	)
