

bin_PROGRAMS = qsub_job_monitor.out

AM_CXXFLAGS = $(BOOST_CPPFLAGS) -ggdb -Wall -std=c++17

qsub_job_monitor_out_SOURCES = qsub_job_monitor/cargs.cc qsub_job_monitor/cargs.h qsub_job_monitor/main.cc qsub_job_monitor/utilities.cc qsub_job_monitor/utilities.h
qsub_job_monitor_out_LDADD = $(BOOST_LDFLAGS) -lboost_program_options -lstdc++fs
dist_doc_DATA = README
ACLOCAL_AMFLAGS = -I m4
