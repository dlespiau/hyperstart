AM_CFLAGS = -Wall

hyperstart_sources=init.c jsmn.c net.c util.c parse.c parson.c container.c exec.c event.c portmapping.c
bin_PROGRAMS=$(HYPERSTART)

if ENABLE_DAEMON
HYPERSTART=hyperstart
hyperstart_SOURCES=$(hyperstart_sources)
else
HYPERSTART=init
init_SOURCES=$(hyperstart_sources)
endif
