add_executable(interval intervalTree.cpp)
target_link_libraries(interval PRIVATE pam)
install(TARGETS interval DESTINATION ${CMAKE_INSTALL_PREFIX}/examples)
