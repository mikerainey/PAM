add_executable(tpch_test test.cpp)
target_link_libraries(tpch_test PRIVATE pam)
install(TARGETS tpch_test DESTINATION ${CMAKE_INSTALL_PREFIX}/examples)
