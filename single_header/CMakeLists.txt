# add a library using the amalgamated header
add_library(ryml ryml/lib.cpp)
target_include_directories(ryml PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
target_compile_features(ryml PUBLIC cxx_std_11)

