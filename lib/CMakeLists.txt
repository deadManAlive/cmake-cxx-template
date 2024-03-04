add_library("${CMAKE_PROJECT_NAME}_Lib" STATIC)

target_sources("${CMAKE_PROJECT_NAME}_Lib"
    PRIVATE
        lib.cpp)