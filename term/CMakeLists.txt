cmake_minimum_required(VERSION 3.4.1)

add_library( jackpal-androidterm5
             SHARED
             src/main/jni/common.cpp
             src/main/jni/termExec.cpp
             src/main/jni/fileCompat.cpp )

target_link_libraries(jackpal-androidterm5
            log )