# macos-darkmode

Your friendly neighbordhood macOS Dark Mode CLI. Dark Mode is set via Apples private APIs instead of the usual Apple Script.

Tested on macOS Mojave (10.14).

## Installing

```console
$ go get -u github.com/mafredri/macos-darkmode/cmd/darkmode
```

## Usage

### Get current Dark Mode

```console
$ darkmode
on
```

### Set Dark Mode

```console
$ darkmode on
$ darkmode off
$ darkmode toggle
```

## Why?

Sometimes setting Dark Mode via Apple Script just doesn't work, I wanted a more reliable method.

## See also

- [macos-brightness](https://github.com/mafredri/macos-brightness): Simple CLI for changing brightness on macOS

## Thanks

Thanks to Saagar Jha for discovering the private APIs and sharing them in his post on [Scheduling Dark Mode](https://saagarjha.com/blog/2018/12/01/scheduling-dark-mode/).
