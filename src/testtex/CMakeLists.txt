set (testtex_srcs testtex.cpp)
add_executable (testtex ${testtex_srcs})
set_target_properties (testtex PROPERTIES FOLDER "Tools")
target_link_libraries (testtex OpenImageIO ${Boost_LIBRARIES} ${CMAKE_DL_LIBS})
