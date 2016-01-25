ALL = daytimetcpcli
CFLAGS = -Wall -g

all: ${ALL}

daytimetcpcli: daytimetcpcli.cpp
	g++ ${CFLAGS} daytimetcpcli.cpp ../libunp.a -I ../lib -o daytimetcpcli

clean:
	rm ${ALL}
