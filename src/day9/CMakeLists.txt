add_executable(day9 day9.cpp)
target_link_libraries(day9 PRIVATE advent_of_code_2022 project_option project_warning fmt::fmt)
target_compile_definitions(day9 PRIVATE INPUT_FILE="${CMAKE_CURRENT_SOURCE_DIR}/day9.txt")
set_property(TARGET day9 PROPERTY BUILD_RPATH "/opt/gcc-11.1.0/lib64")
