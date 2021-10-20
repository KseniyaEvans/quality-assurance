# testing

## Kseniia Lakhman
## KP-82

________________________________________
##### Lab1

Run a server in a docker container:

```shell
cd src
sh server.sh <PORT>
```

`PORT` can be any number from 0 to 65 535.


`telnet` utility can help to browse the server output:

```shell
telnet 127.0.0.1 <PORT>
```

You will see a contents of file and checksum.
To quit from listening press `control + ]`. Then iput `quit` to exit from telnet.