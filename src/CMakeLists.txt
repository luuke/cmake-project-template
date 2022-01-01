add_library(template STATIC template.cpp)

target_include_directories(template
    PUBLIC ${CMAKE_SOURCE_DIR}/include
)
