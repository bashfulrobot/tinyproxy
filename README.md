# Tinyproxy CFG

## About

This is a simple repo with a barebones config to run tinyproxy on my desktop to test the Sysdig agent through a proxy.

## Getting Started

- clone this repository `git clone https://github.com/bashfulrobot/tinyproxy.git`
- `cd tinyproxy`
- run the application `tinyproxy -d -c tinyproxy.conf`
- this will run in the terminal with output on screen. This is not meant to run full time as this is just for testing purposes.

### Installing

- install tinyproxy on Ubuntu `sudo apt install tinyproxy -y`

## Default Configuration

- The proxy server will listen on port 3128
- The proxy server will listen on all addresses
