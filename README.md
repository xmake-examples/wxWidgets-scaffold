# 🌱 wxWidgets Scaffold

A minimal wxWidgets project template

## 🦄 Usage

Simply click the button below to get started:

[![Use this template](https://img.shields.io/badge/use%20this%20template-brightgreen.svg?longCache=true&style=for-the-badge)](https://github.com/xmake-examples/wxWidgets-scaffold/generate)

## 🔨 Development

###  📋 Requirements

To setup and use the project you will need to have the following tools installed:
 - [Xmake](https://xmake.io/)

###  ⬇️ Installation

Clone the repository

```bash
$ git clone https://github.com/xmake-examples/wxWidgets-scaffold.git
```

Change the working directory to the newly cloned repository:

```bash
$ cd wxWidgets-scaffold
```

Run xmake to install the dependencies & build the project:

```bash
$ xmake
note: install or modify (m) these packages (pass -y to skip confirm)?
in xmake-repo:
  -> wxWidgets 3.2.0
please input: y (y/n/m)

  => download https://github.com/wxWidgets/wxWidgets/archive/refs/tags/3.2.0.tar.gz .. ok
  => install wxWidgets 3.2.0 .. ok
[ 25%]: ccache compiling.release src/main.c
[ 50%]: linking.release wxWidgets-scaffold
[100%]: build ok!
```

Run the project after it has been built:

```bash
$ xmake run
```

![](res/example.png)
