project(globals)

make_library(globals
  SOURCES
    globals.cpp
  REQUIRES
    logger
    flexible_type
    EXTERNAL_VISIBILITY
  )
