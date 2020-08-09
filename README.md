# Alpine eBPF

An Alpine-based image for compiling and running eBPF programs.

## Getting Started

This image is intended to be used as the basis for an eBPF C language template compatible with the OpenFaaS serverless framework. Therefore, this image contains only the updated required dependencies for compiling and running eBPF C programs.

### Prerequisities

In order to run this container you'll need docker installed, as well as OpenFaaS.

* [OpenFaaS](https://docs.openfaas.com/)
* [Docker on Linux](https://docs.docker.com/linux/started/)
* [Docker on Windows](https://docs.docker.com/windows/started)
* [Docker on OS X](https://docs.docker.com/mac/started/)

### Usage

You can use this container individually for your own purposes or in conjunction with an OpenFaaS template. To learn more, see this [guide](https://github.com/lucasfsduarte/openfaas-c) written for a C template that uses a similar image as a base.

## Built With

* Alpine build-base v0.5 (includes gcc, g++, make, libc-dev and other packages)
* Python v3.7
* Clang v8.0
* Linux Headers v4.19
* BPFTools & iprouter2

## Author

* **Lucas Duarte** - *Undergraduated student at UFV*

### Find me

* [GitHub](https://github.com/lucasfsduarte)
* [Institutional e-mail](lucas.f.duarte@ufv.br)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
