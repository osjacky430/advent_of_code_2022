add_executable(day15 day15.cpp)
target_link_libraries(day15 PRIVATE advent_of_code_2022 project_option project_warning fmt::fmt ctre::ctre)
target_compile_definitions(day15 PRIVATE INPUT_FILE="${CMAKE_CURRENT_SOURCE_DIR}/day15.txt")
set_property(TARGET day15 PROPERTY BUILD_RPATH "/opt/gcc-11.1.0/lib64")
