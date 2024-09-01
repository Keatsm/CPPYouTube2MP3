# Create a library from the source files
add_library(CPPYouTube2MP3 STATIC
    CPPYouTube2MP3.cpp
)

# Specify include directories for the library
target_include_directories(CPPYouTube2MP3 PUBLIC ../include)

# If the library is public (can be used by other projects)
# Export it for use in other projects
export(TARGETS CPPYouTube2MP3 FILE CPPYouTube2MP3Targets.cmake)
