add_executable(app main.cpp)

target_include_directories(app
    PUBLIC ${CMAKE_SOURCE_DIR}/include
)
target_link_directories(app
    PUBLIC ${CMAKE_SOURCE_DIR}/src
)
target_link_libraries(app
    PUBLIC template
)
