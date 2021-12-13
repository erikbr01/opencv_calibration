
add_executable(opencv_calibration
src/main.cpp
)

target_include_directories(opencv_calibration PUBLIC include)

target_link_libraries(opencv_calibration PRIVATE ${OpenCV_LIBS})


