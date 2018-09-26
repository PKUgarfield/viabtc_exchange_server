TARGET  := accessws.exe
INCS = -I ../network -I ../utils -I ../depends
LIBS = -L ../utils -lutils -L ../network -lnetwork -L ../depends/hiredis -Wl,-Bstatic -lev -ljansson -lmpdec -lrdkafka -lz -lhiredis -llz4 -lssl -lcrypto -lcurl -Wl,-Bdynamic -lm -lpthread -ldl -lldap -llber -lgss -lgnutls -lidn -lnettle -lrtmp -lsasl2 -lmysqlclient
include ../makefile.inc
