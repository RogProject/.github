# Rog Engine

Rog is a roguelike engine written in Go.

## Repository Overview

* `engine` - The main engine code
* `rscript` - The RScript scripting language, used to handle AI and dialogue
* `project-monkey` - The testbed game

## Workspace Setup

Use [Go workspaces](https://go.dev/ref/mod#workspaces) to handle project development. Follow these steps for a quick project setup.

1. `$ mkdir rog`
2. `$ cd rog`
3. `$ git clone git@github.com:RogProject/project-monkey.git`
4. `$ git clone git@github.com:RogProject/rscript.git`
5. `$ git clone git@github.com:RogProject/engine.git`
6. `$ go work init ./project-monkey ./rscript ./engine`

## Running the testbed game

Run the `project-monkey` module to test out features.

```
$ go run ./project-monkey
```
