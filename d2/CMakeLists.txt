project("day2")

add_executable("d2-1" "d2-1.cpp")
add_executable("d2-2" "d2-2.cpp")

TARGET_LINK_LIBRARIES("d2-1" advent-of-code-2020-utils)
TARGET_LINK_LIBRARIES("d2-2" advent-of-code-2020-utils)
