add_library( cpp-peglib INTERFACE )
add_library( cpp-peglib::cpp-peglib ALIAS cpp-peglib )

target_include_directories(
  cpp-peglib
  INTERFACE
  "$<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}>"
)
