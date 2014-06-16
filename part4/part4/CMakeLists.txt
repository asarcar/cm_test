add_library(library SHARED Library.cc)
set_target_properties(library PROPERTIES LIBRARY_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/lib)
message("CMAKE_SOURCE_DIR is \"\${CMAKE_SOURCE_DIR}\"")
set_target_properties(library PROPERTIES OUTPUT_NAME library${BUILD_POSTFIX})