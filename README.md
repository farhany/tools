## Gopei (Go Programming Environment Installer)<br/>The Convergence

[![version](https://img.shields.io/badge/version-1.6-blue.svg)](https://github.com/geosoft1/tools/archive/master.zip)
[![license](https://img.shields.io/badge/license-gpl-blue.svg)](https://github.com/geosoft1/tools/blob/master/LICENSE)

Gopei shell install [Go](http://golang.org) compiler, [LiteIDE](https://github.com/visualfc/liteide) and configure for you the entire environment, variables, paths, ide interface and even link the machine with your Github account in a few minutes with just one command.

You don't need to use complicated commands on Mac or Linux so you just have to write go programs. 

Also, add some high level commands wich help you easy make a repository, clone, push or get a project and more.

This project is third party. For support see [golang.org](http://golang.org) and [github.com/visualfc/liteide](https://github.com/visualfc/liteide).

Read the user manual on the [wiki page](https://github.com/geosoft1/tools/wiki).

**Features**

- Convergence, Gopei run now on many Unix/Linux based desktops and servers (yes, work on Mac).
- Install last versions of Go compiler and a stable version of LiteIDE.
- Create a simple and practical layout for ide (liteide.ini.mini).
- Lot of gophers use Monaco font so add into ide.
- Also create `GOPATH` and add a helloworld project.
- Add a nice launcher to dock or desktop.
- Extend project templates with **Go1 Simple Project** and **Go1 GPL Project**.
- Add some useful scripts for
   - working with git (be sure you have installed `git` before and a valid acount)
   - easy install some useful tools like [delve](https://github.com/derekparker/delve) debugger or [presenter](https://godoc.org/golang.org/x/tools/present)
   - cloud features (next frontier)
- Gopei shell is free as in free speech and free beer...

**What's new in 1.6 (milestone)**

- complete code rewritten, new approach.
- versioning acording to [semantic versioning](http://semver.org), see `dfc` [manifest](http://dave.cheney.net/2016/06/24/gophers-please-tag-your-releases).
- go environment moved into `.go_profile` file also inspired from `dfc` [~/.bashrc](https://forum.golangbridge.org/t/where-to-place-tools/2430/5)

**How to use**

[Download](https://github.com/geosoft1/tools/archive/master.zip) anywhere and unarchive. From Terminal go to the `tools` folder and simply run:

    ./gopei

Use `` -h `` switch to see all options.

Run periodicaly or if compiler/ide versions change to update the system. Projects are never affected if you overinstall.

Note that your system must have `bash`,`curl` and `git` installed before. Also, some systems may need additional packages.

Read the [wiki page](https://github.com/geosoft1/tools/wiki) for more details.

