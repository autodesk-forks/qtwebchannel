# Generated from webchannel.pro.

#####################################################################
## webchannel Plugin:
#####################################################################

qt_internal_add_qml_module(webchannel
    URI "QtWebChannel"
    VERSION "1.0" #special case
    CLASSNAME QWebChannelPlugin
    SKIP_TYPE_REGISTRATION
    SOURCES
        plugin.cpp
    INCLUDE_DIRECTORIES
        ../../webchannel
    PUBLIC_LIBRARIES
        Qt::Core
        Qt::Quick
        Qt::WebChannelPrivate
)

#### Keys ignored in scope 1:.:.:webchannel.pro:<TRUE>:
# IMPORT_VERSION = "1.$$QT_MINOR_VERSION"
# TARGETPATH = "QtWebChannel"
