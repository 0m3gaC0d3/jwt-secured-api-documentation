# JWT secured API - Documentation

This documentation is build with [MkDocs](https://www.mkdocs.org).

## Installation of MkDocs

### Windows

By [chocolatey](https://chocolatey.org/install):

```cmd
choco install mkdocs
```

### Debian/Ubuntu

```shell script
apt-get install mkdocs
```

### MacOS

By [homebrew](https://brew.sh/index_de):

```shell script
brew install mkdocs
```

## Usage

The [MkDocs User-Guide](https://www.mkdocs.org/user-guide/writing-your-docs/) 
can be found [here](https://www.mkdocs.org/user-guide/writing-your-docs/).

### Development

```shell script
mkdocs serve
```

Will run a local webserver on port 8000 where a live preview of the docs are available.

### Build

```shell script
mkdocs build
```

Will generate a **site** folder which can be uploaded to a webserver.
