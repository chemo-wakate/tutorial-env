# tutorial-env

A base docker image for chemo-wakate tutorial.

## Overview

A docker image for chemoinformatics include below tools.  

- Jupyter notebook
- rdkit

## Usage

```
docker pull chemowakate/tutorial-env
```

**Run jupyter notebook on docker container**

```
docker run \
    --rm \
    -it \
    -p 8888:8888 \
    chemowakate/tutorial-env
```
