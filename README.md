# Example of GPU enabled PyTorch install from conda-forge with `pixi`


On a Linux (`linux-64`) or Apple silicon (`osx-arm64`) machine install a GPU enabled version of PyTorch and all dependencies from [conda-forge](https://conda-forge.org/) using [`pixi`](https://pixi.sh/).


## Get started

1. Install [`pixi`](https://pixi.sh/)
2. Run
```
pixi install
```

or optionally just run

```
pixi run start
```

## Verifying

To do a quick check that the installed PyTorch is GPU compatible and detect your machine's GPU run

```
pixi run start
```
