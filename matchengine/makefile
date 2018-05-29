TARGET  := matchengine.exe
INCS = -I ../network -I ../utils
LIBS = -L ../utils -lutils -L ../network -lnetwork -Wl,-Bstatic -lev -ljansson -lmpdec -lmysqlclient \
-lrdkafka -lz -lssl -lcrypto -lrt \
-lhiredis -lcurl -lsqlite3 -lstdc++ -Wl,-Bdynamic -lm -lpthread -ldl -lsasl2
include ../makefile.inc
