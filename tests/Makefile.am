# Network UPS Tools: tests

if HAVE_CPPUNIT

TESTS = cppunittest

check_PROGRAMS = $(TESTS)

cppunittest_CXXFLAGS = $(CPPUNIT_CFLAGS)
cppunittest_LDFLAGS = $(CPPUNIT_LIBS)
cppunittest_LDADD = ../clients/libnutclient.la

# List of src files for CppUnit tests
CPPUNITTESTSRC = example.cpp nutclienttest.cpp

cppunittest_SOURCES = $(CPPUNITTESTSRC) cpputest.cpp

else !HAVE_CPPUNIT

EXTRA_DIST = example.cpp cpputest.cpp

endif !HAVE_CPPUNIT
