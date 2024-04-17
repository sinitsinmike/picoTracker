add_library(
  st7789.h st7789.c
  mpfile.h mpfile.c
)

target_link_libraries(platform_display PUBLIC pico_stdlib
                                       PUBLIC hardware_spi
)

target_include_directories(platform_display PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

include_directories(${PROJECT_SOURCE_DIR})
mpfile.c
Add files via upload
9 minutes ago
mpfile.h
Add files via upload
9 minutes ago
st7789.c
Add files via upload
9 minutes ago
st7789.h
