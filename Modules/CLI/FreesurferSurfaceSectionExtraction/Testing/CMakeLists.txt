
#-----------------------------------------------------------------------------
#set(CLP ${MODULE_NAME})

#add_executable(${CLP}Test ${CLP}Test.cxx)
#add_dependencies(${CLP}Test ${CLP})
#target_link_libraries(${CLP}Test ${ITK_LIBRARIES} ${SlicerExecutionModel_EXTRA_EXECUTABLE_TARGET_LIBRARIES})
#set_target_properties(${CLP}Test PROPERTIES LABELS ${CLP})

#set(testname ${CLP}Test)
#add_test(NAME ${testname} COMMAND ${SEM_LAUNCH_COMMAND} $<TARGET_FILE:${CLP}Test>
#  FreesurferSurfaceSectionExtractionTest --help
#  )
#set_property(TEST ${testname} PROPERTY LABELS ${CLP})
