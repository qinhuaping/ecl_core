###############################################################################
# Files
###############################################################################

file(GLOB HEADERS RELATIVE ${CMAKE_CURRENT_SOURCE_DIR} *.hpp)
  
install(FILES ${HEADERS} DESTINATION ${CATKIN_GLOBAL_INCLUDE_DESTINATION}/ecl/devices/detail)

