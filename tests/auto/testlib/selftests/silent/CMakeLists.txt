# Generated from silent.pro.

#####################################################################
## silent Binary:
#####################################################################

add_qt_executable(silent
    NO_INSTALL # special case
    OUTPUT_DIRECTORY ${CMAKE_CURRENT_BINARY_DIR} # special case
    GUI
    SOURCES
        tst_silent.cpp
    PUBLIC_LIBRARIES
        Qt::TestPrivate
)

## Scopes:
#####################################################################
