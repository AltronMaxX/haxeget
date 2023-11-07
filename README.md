# haxeget
The *easier* way to install and manage Haxe compiler versions

## Installation
The easiest way to install is to use the meta-installer with this one command
```sh
curl --proto '=https' --tlsv1.2 -sSf https://raw.githubusercontent.com/l0go/haxeget/main/meta-install.sh | bash
```

## Usage
```sh
# Here is how we would install version 4.3.2 of the compiler
$ haxeget install 4.3.2
$ haxeget use 4.3.2
$ haxe # Can now run haxe and haxelib freely
```

If needed, we can install another version and switch freely between them with the ``haxeget use <version>`` command.

## Why Rust?
I wanted to mess with the Rust programming language and this seemed like a decent opportunity. If I had proper hindsight, I would have written it in a better language like Go, Zig, or even godforbid Haxe itself.1
