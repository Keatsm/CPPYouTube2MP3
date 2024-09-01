cmake_minimum_required(VERSION 3.10)
project(CPPYouTube2MP3 VERSION 1.0.0)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Include directories
include_directories(include)

# Add subdirectories for building
add_subdirectory(src)

# Optionally, define installation rules
install(TARGETS CPPYouTube2MP3 DESTINATION lib)
install(DIRECTORY include/CPPYouTube2MP3 DESTINATION include)
