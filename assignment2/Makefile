CC:= gcc
CFLAGS:= --std=c17 

all: server client

server:server.c
	$(CC) $(CFLAGS) -o server server.c
client:client.c
	$(CC) $(CFLAGS) -o client client.c

clean : 
	rm server client
	@echo "assignment2, output files are removed."
	