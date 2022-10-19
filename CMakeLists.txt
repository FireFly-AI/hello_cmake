#cmake_minimum_required(2.8)
project(Hello_Cmake)


aux_source_directory(${CMAKE_CURRENT_SOURCE_DIR}/src/ HELLO_CMAKE_SRC_LIST)

add_executable(Hello_Cmake 
    ${HELLO_CMAKE_SRC_LIST}
)