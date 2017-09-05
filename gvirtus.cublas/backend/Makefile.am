backendlibdir = $(libdir)/backend
backendlib_LTLIBRARIES = libcublas-backend.la
libOpencl_backend_la_SOURCES = \
CublasHandler.cpp\
CublasHandler.h\
libCublas_backend_la_AMCXXFLAGS = -fPIC -fpermissive
libCublas_backend_la_CXXFLAGS = -fpermissive
libCublas_backend_la_LIBADD = $(CUBLAS_LIB_FLAGS) -lrt -lcublas

