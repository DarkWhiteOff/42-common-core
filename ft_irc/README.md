# ft_irc

ft_irc is a C++ networking project from the 42 School common core curriculum.

The goal of the project is to build an IRC server compatible with standard IRC clients. It handles multiple clients simultaneously, user authentication, channels, private messages and core IRC commands.

## Features

- TCP server using sockets
- Multiple client handling
- User authentication with server password
- Nickname and username registration
- Channel creation and management
- Private messages
- Operator privileges
- IRC command parsing
- Compatibility with IRC clients

## Concepts

- C++ programming
- Network programming
- TCP/IP sockets
- I/O multiplexing
- Client-server architecture
- Protocol parsing
- Object-oriented design

## Usage

Compile the project:

```bash
make
```

Run the server:

```bash
./ircserv <port> <password>
```

Example:

```bash
./ircserv 6667 mypassword
```

Then connect using an IRC client such as `irssi`, `HexChat` or another compatible client.

Clean generated files:

```bash
make fclean
```

## Note

This project was developed as part of the 42 School curriculum and follows the project constraints defined by the subject.