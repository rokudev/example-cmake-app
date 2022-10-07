add_executable(neil_armstrong neil.cpp)

target_compile_options(neil_armstrong PRIVATE -Wall -Wextra -Wno-unused-variable -Werror)

set_target_properties(neil_armstrong PROPERTIES VERSION ${PROJECT_VERSION})

install(TARGETS neil_armstrong)
