# IP Sniffer
My basic implementation of ip sniffer in Rust

## Features

- Scan open ports on a given IP address.
- Multithreaded scanning for improved performance.
- Command-line interface with helpful usage instructions.

## Usage

### Build the Project

To build the project, run the following command:

```sh
cargo build
```

### Run the Project
To run the project, use:

```sh
cargo run -- <arguments>
```

### Command-Line Arguments
- -j <number>: Specify the number of threads to use for scanning.
- -h or -help: Display usage instructions.

### Example
This command scans the IP address 192.168.1.1 using 4 threads.
```sh
cargo run -- -j 4 192.168.1.1
```
