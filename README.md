# 📡 minitalk — Interprocess Communication Using UNIX Signals

## 🧭 Project Description

**minitalk** is a 42 School project that explores **interprocess communication (IPC)** using only **UNIX signals**.

The objective is to create two programs:

- **Server** — receives messages
- **Client** — sends messages

The client sends a string to the server **bit by bit**, using only the signals:

- `SIGUSR1`
- `SIGUSR2`

This project teaches how processes communicate at a very low level without sockets, pipes, or shared memory.

---

## 🎯 Learning Objectives

With minitalk, you learn to:

- Use UNIX signals for communication
- Encode and decode data at the bit level
- Manage asynchronous events
- Handle signal timing and synchronization
- Work with process IDs (PID)
- Write signal-safe and robust code
