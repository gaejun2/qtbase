# Generated from evdevmouse.pro.

#####################################################################
## QEvdevMousePlugin Plugin:
#####################################################################

qt_add_plugin(QEvdevMousePlugin
    OUTPUT_NAME qevdevmouseplugin
    TYPE generic
    SOURCES
        main.cpp
    PUBLIC_LIBRARIES
        Qt::Core
        Qt::CorePrivate
        Qt::Gui
        Qt::GuiPrivate
        Qt::InputSupportPrivate
)

#### Keys ignored in scope 1:.:.:evdevmouse.pro:<TRUE>:
# OTHER_FILES = "evdevmouse.json"
# PLUGIN_EXTENDS = "-"
