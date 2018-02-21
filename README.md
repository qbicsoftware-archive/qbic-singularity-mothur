# Containers for QBIC


[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/626)


This is the central template repository for creating Singularity containers being used at [QBIC](https://qbic.life) in Tübingen, Germany.

For further information or help, please contact: alexander.peltzer@qbic.uni-tuebingen.de. 

## Documentation

### Image sizes

To keep image sizes as small as possible, we use the Alpine Linux base image (only 5MB in size)! instead of using full-size dependencies that we dont want to have in our environment at all. 

### Template Image

The template Singularity file can be found in the root of this repository. Please rename the file according to our SOP to `Singularity.<toolname/pipeline-name>` or accordingly. Accompanying this, a `build.sh` file is also stored here, typically used to install stuff in the image environment. If you have multiple versions, copy the `Singularity.latest` file and keep it as a specific version there. 

## Author

* [Alexander Peltzer](https://github.com/apeltzer)
