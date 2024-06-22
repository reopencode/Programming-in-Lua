# Programming-in-Lua

![](./logo.png)

This is a simple tutorial to the Lua programming language.\
We use last version of Lua (currently is 5.4.6) to learning.
<!--- This tutorial has 3 level to learning:
-  Basic<br />
- Intermediate<br />
- Advanced<br />

-->

## Basic

### Introduction
Lua is one of the simplest general purpose programming languages, and it is a small language and easy to learn.\
Lua is dynamically typed, safe environment, no redundancies, automatic memory management, ease of testing and debugging and facilities for handling strings and other kinds of data with dynamic size. with this capabilities Lua is widely used in embedded systems, mobile devices, the iot, and games.\
Lua offres a set of features like:
- **Extensibility**:
Lua to be extended, both through Lua code and Through external C code.<!---As a proof of concept, just need search.-->
- **Simplicity**:
Lua is a simple and small language, and easy to learn.
- **Efficiency**:
one of the fastest scripting language.
- **Portability**:
Lua can running on all platforms: all flavors of UNIX (Linux, FreeBSD, etc), Windows, Android, iOS, game consoles(PS, etc), and so.

Many gaming engines provide scripting via Lua, one of the most popular is Roblox. More software like some of security applications, some network scanners like Nmap, Redis and so, use Lua for scripting.\
Lua is primarily used as an embedded language to enable scripting in your own programs, written in C or C++ or other similar languages.

For the purposes of this tutorial, we will use the Lua Interpreter as the programming environment. It is the official Lua language.\
Another popular environment is LuaJIT, which does a just-in-time (like java), compile to machine code during program execution.\
Lua has unofficial and customized various, one of popular called luau, that is used in Roblox.\
Maybe you find some of the various for some of purpose.\
Like another programming language, Lua has a package manager for self. It is called **LuaRocks**. It allows you to install Lua modules as self-contained packages called rocks, which also contain version dependency information.

#### How to get Lua
1- If you know how to compile C code in your machine, you must download last version of Lua source code (at this time 5.4.6) from [Lua.org](https://www.lua.org/download.html) and compile it.\
2- You can download precompiled Lua interpreters from Lua Binaries site.\
3- In Linux you can get some version of Lua with *apt install* command.

#### How to run Lua
1- write your code in a file with postfix *.lua*, and give that file to the Lua interpreter.
Linux example:\
`$ lua main.lua`

2- Lua interpreter provided an argument to execute script without file (*-e*).
For example:\
`$ lua -e "print('Hello,World!')"`

3- also we can use interactive mode of Lua interpreter.\
In the interactive mode, Lua processes the input one line at a time.\
How to go in the interactive mode:\
write lua in command line and press enter:)


### Getting Started


## Intermediate


## Advanced

