# TCP_PORT_SCANNER-[GO]
# 🔍 Go TCP Port Scanner

This is a simple TCP port scanner written in Go. It prompts the user for a domain or IP address and scans ports **1 through 1024** to identify which ones are open.

## 📦 Features

- Scans the most common 1024 TCP ports
- Command-line interface for real-time user input
- Lightweight, no external dependencies beyond Go standard library
- Great for learning basic networking and Go's `net` package

## 🛠 How It Works

1. The program prompts the user to enter a target website or IP address.
2. It attempts to establish a TCP connection to each port from 1 to 1024.
3. If the connection is successful, the port is considered open and is printed to the console.

## 🧪 Example

