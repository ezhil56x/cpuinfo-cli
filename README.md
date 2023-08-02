# CPU Info CLI Tool

## Introduction

CPU Info is a simple CLI tool to monitor system metrics, including the number of CPU cores, CPU percentage, and load average. The tool utilizes the `psutil` library to gather system information. This uses Python's `optparse` module to parse command-line arguments.

## Requirements

- Python 3.x
- psutil library

## Usage

To use the application, you can run the script with various options as follows:

```bash
cpuinfo -n       # Print the number of CPU cores
cpuinfo -c       # Print the CPU percentage
cpuinfo -l       # Print the load average
cpuinfo -s       # Continuously stream the values
cpuinfo -h       # Print the help message
```

## Installation

To install CPU Info CLI Tool, follow these steps

1. Clone the repository

```bash
git clone https://github.com/ezhil56x/cpuinfo-cli.git
```

2. Change the working directory

```bash
cd cpuinfo-cli
```

3. Install the psutil library

```bash
pip install psutil
```

4. Make the script executable

```bash
chmod +x cpuinfo
```

5. Move the script to the bin directory

```bash
sudo mv cpuinfo /usr/bin
```

6. Run the script with the help option

```bash
cpuinfo -h
```
