ACLOCAL_AMFLAGS=-I ../../m4
AM_CPPFLAGS=-I${top_srcdir} -I${top_builddir} -I${top_srcdir}/libpolys -I${top_builddir}/libpolys \
${FACTORY_INCLUDES} $(OMALLOC_INCLUDES) $(RESOURCES_INCLUDES) \
${NTL_CFLAGS} $(FLINT_CFLAGS) ${GMP_CFLAGS}

noinst_LTLIBRARIES=libGBEngine.la
libGBEngine_la_SOURCES=khstd.cc kstdfac.cc kstd1.cc kstd2.cc kutil.cc nc.cc sca.cc gr_kstd2.cc kspoly.cc kpolys.cc syz.cc syz0.cc syz1.cc syz2.cc syz3.cc units.cc tgb.cc tgbgauss.cc f5data.cc f5lists.cc f5gb.cc f5c.cc ratgring.cc shiftgb.cc ringgb.cc janet.cc

libGBEngine_la_includedir=$(includedir)/kernel/GBEngine
libGBEngine_la_include_HEADERS=stairc.h syz.h kstdfac.h kutil.h khstd.h kstd1.h units.h ratgring.h shiftgb.h nc.h kInline.h tgb.h ringgb.h tgbgauss.h tgb_internal.h f5c.h f5data.h f5gb.h f5lists.h janet.h



