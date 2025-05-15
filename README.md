# Digital Signatures Implementation

This project implements digital signatures using RSA and SHA-1 algorithms. It includes both client and server components for secure communication.

## Components

- `client.c`: Client implementation for sending signed messages
- `server.c`: Server implementation for verifying received messages
- `rsa.c` & `rsa.h`: RSA implementation for digital signatures
- `sha1.c` & `sha1.h`: SHA-1 hash function implementation

## Building

To build the project, use the following commands:

```bash
gcc -o client client.c rsa.c sha1.c
gcc -o server server.c rsa.c sha1.c
```

## Usage

1. Start the server:
```bash
./server
```

2. Run the client:
```bash
./client
```

## Security Features

- RSA-based digital signatures
- SHA-1 message hashing
- Secure key generation and management 