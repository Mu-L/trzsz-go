# trzsz-go
trzsz is a simple file transfer tools, similar to lrzsz ( rz / sz ), and compatible with tmux.


## Installation

### on Ubuntu
*Not released yet, please download the latest [release](https://github.com/trzsz/trzsz-go/releases) from GitHub.*

```sh
sudo add-apt-repository ppa:trzsz/ppa
sudo apt update
sudo apt install trzsz
```


### on Windows / macOS / Other

Please download the latest [release](https://github.com/trzsz/trzsz-go/releases) from GitHub.


### install from Source Code

```sh
git clone https://github.com/trzsz/trzsz-go.git
cd trzsz-go
make
sudo make install
```


## Usage

### on Local

Add `trzsz` before the shell, e.g.:

```sh
trzsz tmux
trzsz /bin/bash
trzsz ssh x.x.x.x
trzsz.exe cmd
trzsz.exe ssh x.x.x.x
```


### on Server

*The `Go` version is under development. Please use the `Python` version instead. GitHub: https://github.com/trzsz/trzsz*

Similar to lrzsz ( rz / sz ), command `trz` to upload files, command `tsz /path/to/file` to download files.

For more information, see the website of trzsz: [https://trzsz.github.io](https://trzsz.github.io/).


## Contact

Feel free to email me <lonnywong@qq.com>.
