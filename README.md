# Chat

Simple TCP chat built with [Golang](https://go.dev)

## Install

### Using [Go install](https://go.dev/ref/mod#go-install)

```console
$ go install github.com/colaxdev/chat@latest
```

### From binary package

Go to [Releases](https://github.com/colaxdev/chat/releases)

## Quick Start

### Run server

```console
$ chat
```

### Connect to server using [Telnet](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/telnet)

```console
$ telnet 127.0.0.1 8080 
```

## Commands

- `/nick <name>` - get a name, otherwise user will stay anonymous.
- `/join <name>` - join a room, if room doesn't exist, the new room will be created. User can be only in one room at the same time.
- `/rooms` - show list of available rooms to join.
- `/msg <msg>` - broadcast message to everyone in a room.
- `/quit` - disconnects from the chat server.
