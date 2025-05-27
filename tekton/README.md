# CoreOS task and pipelines

This directory contains the CoreOS Tekton tasks and pipelines definitions used to create the associated bundles.
The bundle references get built in Konflux and are published to a registry.
Those bundles are then consumed in Konflux pipelines to produced the desired artefacts.

Please refer to https://github.com/konflux-ci/build-definitions for more information on how to build and tests tasks.

We can also use the helper scripts that live in https://github.com/konflux-ci/build-definitions/tree/main/hack e.g `generate-readme.sh` to generate a task README or `generate-pipelines-readme.py` for a pipeline.
