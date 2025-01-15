cmake_minimum_required(VERSION 3.16)

project(CharVolant)

add_subdirectory(Source)

set_property(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR} PROPERTY VS_STARTUP_PROJECT CharVolant)
