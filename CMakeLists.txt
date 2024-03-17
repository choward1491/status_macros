add_library(status_macros)
target_include_directories(status_macros PRIVATE ${CMAKE_CURRENT_LIST_DIR}/)
target_sources(status_macros PUBLIC
               status.h
               status.cc
               status_builder.cc
               status_builder.h
               status_macros.h
               source_location.h)