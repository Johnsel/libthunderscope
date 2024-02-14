add_executable(litepcie_test litepcie_test.cpp)

target_link_libraries(litepcie_test litepcie)

if(WIN32)
    target_link_libraries(litepcie_test setupapi)
endif()