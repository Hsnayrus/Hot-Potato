CPPFLAGS = -Wall -Werror -pedantic -ggdb3 -std=c++11

.PHONY: clean
 
all: player ringmaster

ringmaster: RingMaster.cpp
	g++  -o ringmaster $(CPPFLAGS) RingMaster.cpp

player: player.cpp
	g++  -o player $(CPPFLAGS) player.cpp

clean:
	rm -rf ringmaster player *.dSYM