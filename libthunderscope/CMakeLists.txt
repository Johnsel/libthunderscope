add_library(libthunderscope libthunderscope.cpp)
target_link_libraries(libthunderscope litepcie)

if(WIN32)
    target_link_libraries(libthunderscope setupapi)
endif()