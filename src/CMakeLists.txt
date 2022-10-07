add_executable(neil_armstrong neil.cpp)

target_compile_options(neil_armstrong PRIVATE -Wall -Wextra -Wno-unused-variable -Wno-unused-parameter -Werror)

set_target_properties(neil_armstrong PROPERTIES VERSION ${PROJECT_VERSION})

target_link_libraries(
    neil_armstrong
    -lsaturn
    -ltitan
    -leuropa
    -ljupiter
)

install(TARGETS neil_armstrong)
