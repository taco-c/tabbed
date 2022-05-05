# tabbed - generic tabbed interface

tabbed is a simple tabbed X window container.

## Requirements
In order to build tabbed you need the Xlib header files.

### \*buntu
```
sudo apt install libx11-dev libxft-dev
```

## Installation
Edit config.mk to match your local setup (tabbed is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install tabbed
(if necessary as root):

```sh
make clean install
```

## Running tabbed
See the man page for details.

