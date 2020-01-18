project(proto)

set(CMAKE_CXX_STANDARD 11)

add_library(${PROJECT_NAME} STATIC cpp/AppMsg.pb.cc cpp/AlarmMsg.pb.cc)
target_include_directories(${PROJECT_NAME} PUBLIC ./cpp)
