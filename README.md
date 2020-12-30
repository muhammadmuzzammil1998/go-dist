# go-dist

Distribution script for programs written in Go

## Usage

First of all, navigate to your `go` source directory where you run `go build` command to build the binary. Then follow these -

### Making `.dist` directory and navigating to it

```bash
$ mkdir .dist
$ cd .dist
```

### `git` it

```bash
$ git clone https://github.com/muhammadmuzzammil1998/go-dist .
```

Don't forget to clone in the same directory `(.)`

### Making `build.sh` executable

```bash
$ chmod 777 ./build.sh
```

### Running `build.sh`

```bash
$ ./build.sh
```

## Working with `build.sh`

[![asciicast](https://asciinema.org/a/381907.svg)](https://asciinema.org/a/381907)

## Couple of things to note

1. You should be in the main go directory of your project. That is, the place you run `go test`, `go build` etc. commands.
2. This repository (go-dist) should be a direct sub-directory to the main go directory. Structure should look like this:

```
- ./
-- main.go
-- other_files.Go
-- main_test.Go
-- README.md
-- .dist/
-- -- build.sh

```
