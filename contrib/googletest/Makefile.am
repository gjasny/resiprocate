noinst_LTLIBRARIES = libgmock.la libgmock_main.la

AM_CXXFLAGS = -isystem $(srcdir)

libgmock_la_SOURCES = gmock-gtest-all.cc gmock/gmock.h gtest/gtest.h

libgmock_main_la_SOURCES = gmock_main.cc
libgmock_main_la_LIBADD = libgmock.la
