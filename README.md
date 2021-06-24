<p align="center"><a href="#readme"><img src="https://gh.kaos.st/pkgre-godoc-action.svg"/></a></p>

<br/>

Action for generating docs for packages that use [`pkg.re`](https://pkg.re) service.

### Usage

Create file `.github/workflows/godoc.yml`.

Add next code to it:

```yml
name: GoDoc

on:
  create

jobs:
  GoDoc:
    name: Generate docs
    runs-on: ubuntu-latest

    steps:
      - name: Trigger GoSumDB and PkgGoDev
        uses: essentialkaos/pkgre-godoc-action@v1

```

### License

[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)

<p align="center"><a href="https://essentialkaos.com"><img src="https://gh.kaos.st/ekgh.svg"/></a></p>
