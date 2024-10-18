# sk1ddymap  
The Modern Port Scanner 
 
## Overview
sk1ddymap is an advanced multi-threaded port scanner that allows you to scan a range of ports on any target system. It's designed to be fast, efficient, and customizable. Users can download the precompiled binary for their platform and start scanning without needing to view or modify the source code.

## Features
- Multi-threaded scanning for faster results
- Service identification for common ports
- Output results in JSON format
- Simple CLI interface

## Download
You can download the precompiled binaries or `.deb` package from the [Releases](https://github.com/z3kyz/sk1ddymap/releases/tag/v1.0.0) section:

- [Linux (.deb package)](https://github.com/z3kyz/sk1ddymap/releases/download/v1.0.0/sk1ddymap_1.0.0.deb)


## Installation (Linux `.deb` Package)
To install the `.deb` package on a Debian-based Linux distribution (e.g., Ubuntu, Kali Linux), run the following command:

```bash
sudo dpkg -i sk1ddymap_1.0.0.deb


**After installation, you can run the tool using:**

```bash
sk1ddymap <target> --start-port <start-port> --end-port <end-port> --threads <number-of-threads>
