# AskOmics website

[![Build Status](https://travis-ci.org/askomics/website.svg?branch=master)](https://travis-ci.org/askomics/website)

AskOmics website, build with [Nikola](https://getnikola.com/)


## Installation

### Install dependencies

```bash
# Debian/Ubuntu
sudo apt install -y git make python3 python3-venv
# Fedora
sudo dnf install -y git make python3 python3-virtualenv
```

### Download and install website

```bash
git clone https://github.com/askomics/website.git askomics_website
cd askomics_website
make install
```
```
Bash is the shell, or command language interpreter, for the GNU operating system.
```

## Deployment

```Make
Bash Build
```

Generated html are in the `output` directory


## Developement

### Serve website locally

```Make Serve
     Bash
```

### Create a page

```Make
 A Bash Page
```

The new page will be created in the `pages` directory

### Create a post

``Make
A Bash Post
```

The new post will be created in the `posts` directory
