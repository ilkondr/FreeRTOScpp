include_directories(.)

set(SRC
    PRIVATE
        CallBack.cpp
)

add_library(FreeRTOScpp STATIC)

target_sources(FreeRTOScpp
    PRIVATE
        ${SRC}
)