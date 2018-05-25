# Our binary is produced here
bin_PROGRAMS = ha_server
ha_server_SOURCES = main.cpp \
               event_monitor.h \
               event_monitor.cpp \
               serial_line_monitor.h \
               serial_line_monitor.cpp \
               udp_server.cpp \
               udp_server.h  \
               push_notification.cpp \
               push_notification.h
# main binary will be installed into the default directory for "bin"s (hence we used the bin
# prefix
#noinst_LIBRARIES = libhelper.a
#libhelper_a_SOURCES = helper.cpp helper.h
# noinst_ : assures that this library is not installed to the user's computer
# libBLAH.a is a *nix convention. If you noticed, we replaced the . with _ in SOURCES line.
#main_LDADD = libhelper.a ../my_inc/libmyadd.a
# LDADD specifies which libraries to compile into "main". We have two libraries.
# libhelper comes from this directory and libmyadd come from my_inc directory.
