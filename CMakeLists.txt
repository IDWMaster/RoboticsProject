add_executable(roboproject main.cpp)
SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -I. -std=c++11 -g")
include_directories(${EXTRA_HEADERS} "${PROJECT_BINARY_DIR}" ".")
target_link_libraries(roboproject dl rt ${EXTRA_LIBS})
