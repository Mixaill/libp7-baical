cmake_policy(SET CMP0063 NEW)
include_directories(${P7_Headers})

set(SOURCE
   Main.cpp
)

add_executable(p7-cpp-example ${SOURCE})
target_link_libraries(p7-cpp-example P7)
