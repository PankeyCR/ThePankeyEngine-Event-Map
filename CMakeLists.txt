cmake_minimum_required(VERSION 3.15)

project(ThePankeyEngine_Event_Map)

if(NOT TARGET ThePankeyEngine_Event_Map)

    add_library(ThePankeyEngine_Event_Map INTERFACE)

    target_include_directories(
        ThePankeyEngine_Event_Map
        INTERFACE
            ${CMAKE_CURRENT_SOURCE_DIR}
    )

endif()
