cmake_minimum_required(VERSION 2.8)

project(Samples)

add_subdirectory(${PROJECT_SOURCE_DIR}/Daemon)
add_subdirectory(${PROJECT_SOURCE_DIR}/WatchDog)
add_subdirectory(${PROJECT_SOURCE_DIR}/DaemonAndWatchDog)
add_subdirectory(${PROJECT_SOURCE_DIR}/RunSingleInstance)
add_subdirectory(${PROJECT_SOURCE_DIR}/DaemonAndRunSingleInstance)
add_subdirectory(${PROJECT_SOURCE_DIR}/BindCPU)
