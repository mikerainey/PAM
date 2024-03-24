add_executable(timeOps timeOps.cpp)
target_link_libraries(timeOps PRIVATE pam)
install(TARGETS timeOps DESTINATION ${CMAKE_INSTALL_PREFIX}/benchmark)
