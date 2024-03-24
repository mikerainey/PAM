add_executable(index index.cpp)
target_link_libraries(index PRIVATE pam)
install(TARGETS index DESTINATION ${CMAKE_INSTALL_PREFIX}/examples)
