add_executable(day3 day3.cpp)
target_link_libraries(day3 PRIVATE advent_of_code_2022 project_option project_warning fmt::fmt)
target_compile_definitions(day3 PRIVATE INPUT_FILE="${CMAKE_CURRENT_SOURCE_DIR}/day3.txt")
set_property(TARGET day3 PROPERTY BUILD_RPATH "/opt/gcc-11.1.0/lib64")
