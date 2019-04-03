# Dockerfile for [ANDES](https://github.com/cuihantao/andes)

The Dockerfile in this repository builds a Ubuntu 18.04 environment with ANDES installed in Python 3. 

## Build

Run `docker build . --tag andes:latest` in the repository to build the image.

## Run

To run a container with ANDES in the interactive mode, run

`docker run -it -v <path-to-cases>:/cases andes`

Replace `<path-to-cases>` with the path to the ANDES test cases in your host system.

If successful, the command line prompt line should look like `root@51b9e0f244b7:/#`. You can invole by running `andes`.

Go to the test case volume with `cd /cases` and start using.
