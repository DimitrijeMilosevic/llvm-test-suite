if(NOT "${TARGET_OS}" STREQUAL "AIX")
  add_subdirectory(espresso)
  add_subdirectory(gs)
endif()
if(NOT "${ARCH}" STREQUAL "Alpha")
  add_subdirectory(cfrac)
endif()
