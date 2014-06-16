add_executable(test Test.cc)
target_link_libraries(test library)
set_target_properties(test PROPERTIES RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/bin)
set_target_properties(test PROPERTIES OUTPUT_NAME test${BUILD_POSTFIX})