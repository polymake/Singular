ACLOCAL_AMFLAGS=-I ../../m4
AM_CPPFLAGS=-I${top_srcdir} -I${top_builddir} -I${top_srcdir}/libpolys -I${top_builddir}/libpolys \
${FACTORY_INCLUDES} $(OMALLOC_INCLUDES) $(RESOURCES_INCLUDES) \
${NTL_CFLAGS} $(FLINT_CFLAGS) ${GMP_CFLAGS}

noinst_LTLIBRARIES=libcombinatorics.la
libcombinatorics_la_SOURCES=hdegree.cc hilb.cc hutil.cc

libcombinatorics_la_includedir=$(includedir)/kernel/combinatorics
libcombinatorics_la_include_HEADERS=hutil.h



