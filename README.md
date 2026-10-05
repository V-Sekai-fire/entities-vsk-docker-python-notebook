# entities-vsk-docker-python-notebook

A GPU notebook container, and a predictor that fine-tunes the RF-DETR detector on an uploaded dataset and returns the trained weights.

## Build and run

```sh
docker build docker
cog build
```

The first builds the notebook image, and the README beside its Dockerfile covers running it. The second packages the predictor that `cog.yaml` describes.

## Licence

MIT; see LICENSE.
