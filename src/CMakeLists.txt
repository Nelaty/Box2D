file(GLOB_RECURSE box2d_files_cpp "*.cpp" "*.c" "*.cxx")
file(GLOB_RECURSE box2d_files_h "*.h" "*.hpp")

set(box2d_source_files ${box2d_files_cpp} ${box2d_files_h})
add_library(box2d STATIC ${box2d_source_files})