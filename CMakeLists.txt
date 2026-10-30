cmake_minimum_required(VERSION 3.16)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
# Build the node and its declared dependencies instead of every IDF component.
idf_build_set_property(MINIMAL_BUILD ON)
project(rd03d_radar_node)
