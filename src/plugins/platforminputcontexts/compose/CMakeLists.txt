# Generated from compose.pro.

#####################################################################
## QComposePlatformInputContextPlugin Plugin:
#####################################################################

qt_find_package(XKB) # special case
pkg_get_variable(PKG_X11_PREFIX x11 prefix) # special case
qt_add_plugin(QComposePlatformInputContextPlugin
    OUTPUT_NAME composeplatforminputcontextplugin
    TYPE platforminputcontexts
    SOURCES
        qcomposeplatforminputcontext.cpp qcomposeplatforminputcontext.h
        qcomposeplatforminputcontextmain.cpp
    LIBRARIES
        XKB::XKB
    PUBLIC_LIBRARIES
        Qt::Core
        Qt::CorePrivate
        Qt::Gui
        Qt::GuiPrivate
)

#### Keys ignored in scope 1:.:.:compose.pro:<TRUE>:
# OTHER_FILES = "$$PWD/compose.json"
# PLUGIN_EXTENDS = "-"
