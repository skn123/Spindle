INCLUDES =  -I$(top_srcdir)/include

noinst_LIBRARIES = libjunk.a
libjunk_a_SOURCES = \
	OrderingAlgorithm.cc \
	RCMEngine.cc \
	SloanEngine.cc \
	MinPriorityEngine.cc \
	MinPriorityStrategies.cc 

includedir = $(prefix)/include/spindle
include_HEADERS = $(libjunk_a_SOURCES:.cc=.h)
