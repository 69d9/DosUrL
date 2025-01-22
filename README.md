# DosUrL - DoS Attack Tool

**DosUrL** is a tool designed for conducting **Denial of Service (DoS)** attacks, specifically targeting websites and services. It allows security professionals and network administrators to assess the robustness of networks under simulated attack conditions.

## Features
- Simple and effective DoS testing tool.
- Allows you to specify the target server IP, port, and threads.
- Provides a lightweight solution for security assessments and network stress testing.

## Options
- **-p PORT, --port PORT**: Define the target port, default is 8080
- **-t THREADS, --threads THREADS**: Set the number of threads to use, default is 150 
- **-u, --url**: Specify the target URL or IP address 
- **-h, --help**: Show the help menu

## Example

dosurl -p 80 -t 125 example.com

## Installation

### For Linux
To install DosUrL on a Linux machine, run the following commands:

```bash
wget -O dosurl_1.0_all.deb https://github.com/69d9/DosUrL/releases/download/v1.0/dosurl_1.0_all.deb
sudo dpkg -i dosurl_1.0_all.deb
