# Tinyproxy CFG

## Table of Contents

- [Tinyproxy CFG](#tinyproxy-cfg)
  - [Table of Contents](#table-of-contents)
  - [About <a name = "about"></a>](#about-)
  - [Getting Started <a name = "getting_started"></a>](#getting-started-)
    - [Installing <a name = "installing"></a>](#installing-)

## About <a name = "about"></a>

This is a simple repo with a barebones config to run tinyproxy on my desktop to test the Sysdig agent through a proxy.

## Getting Started <a name = "getting_started"></a>

- clone this repository `git clone https://github.com/bashfulrobot/tinyproxy.git`
- `cd tinyproxy`
- run the application `tinyproxy -d -c tinyproxy.conf`
- this will run in the terminal with output on screen. This is not meant to run full time as this is just for testing purposes.

### Installing <a name = "installing"></a>

- install tinyproxy on Ubuntu `sudo apt install tinyproxy -y`
