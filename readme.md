# Go Starter Kit

A simple template to help get a new project started.

## Check Out the Code

Code is contained in `src/go_starter.go`
Go convention is actually not to use a src folder, but I find it helpful to have top-level scripts, and it starts to get cluttered.

## Install
Install all modules defined in go.mod:
```bash
go install
```

## Run the Code
```bash
./run.sh
```

## Build the Code

```bash
./build.sh
```

This outputs to the dist folder, which is gitignored by default.

## Install testing library

```bash
go get github.com/stretchr/testify/assert
```

## Run Tests

```bash
./test.sh
```

These scripts don't really add much functionality beyond what go makes available via the CLI but they are useful to get started, especially if you're used to JS projects with scripts defined in `package.json`
