cmake_minimum_required(VERSION 3.15)
first-branch
project(obj_det)

set(OpenCV_DIR "C:/Users/araqe/Downloads/opencv/build")
find_package(OpenCV REQUIRED)
add_executable(main main.cpp)
include_directories( ${OpenCV_INCLUDE_DIRS} )
target_link_libraries(main ${OpenCV_LIBS} )
=======
project(ObjDetection)

set(OpenCV_DIR "C:/Users/eganyanc333/Documents/git_repos/ObjDetection/opencv/build")
find_package(OpenCV REQUIRED)
add_executable(main main.cpp)
include_directories( ${OpenCV_INCLUDE_DIRS} )
target_link_libraries(main ${OpenCV_LIBS} )
main
