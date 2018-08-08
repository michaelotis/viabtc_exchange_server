TARGET  := accessws
INCS = -I ../network -I ../utils
LIBS = -L ../utils -lutils -L ../network -lnetwork -Wl,-Bstatic -lev -ljansson -lmpdec -lrdkafka -lcurl -lz -lssl -lcrypt -lcrypto -lhiredis -Wl,-Bdynamic -lm -lpthread -ldl
include ../makefile.inc
