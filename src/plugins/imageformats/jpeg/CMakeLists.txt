# Generated from jpeg.pro.

qt_find_package(JPEG) # special case

#####################################################################
## QJpegPlugin Plugin:
#####################################################################

qt_add_plugin(QJpegPlugin
    OUTPUT_NAME qjpeg
    TYPE imageformats
    SOURCES
        main.cpp main.h
        qjpeghandler.cpp qjpeghandler_p.h
    PUBLIC_LIBRARIES
        JPEG::JPEG
        Qt::Core
        Qt::CorePrivate
        Qt::Gui
        Qt::GuiPrivate
)

#### Keys ignored in scope 1:.:.:jpeg.pro:<TRUE>:
# OTHER_FILES = "jpeg.json"
