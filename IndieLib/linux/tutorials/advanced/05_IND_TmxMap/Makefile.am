bin_PROGRAMS = tutorial5

AM_CXXFLAGS = $(INTI_CFLAGS) -I @top_srcdir@/../common/include -I @top_srcdir@/../tutorials/advanced/05_IND_TmxMap -I @top_srcdir@/../tutorials

tutorial5_SOURCES = ../../../../tutorials/WorkingPath.cpp  ../../../../tutorials/advanced/05_IND_TmxMap/CIndieLib.cpp ../../../../tutorials/advanced/05_IND_TmxMap/Tutorial05.cpp

tutorial5_LDADD = -L@top_srcdir@/.libs $(INTI_LIBS) -lIndieLib -lSDL2 -lGLEW -lGLU -lGL
