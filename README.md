Build Flannel in a Docker Container
===================================

## Usage

`docker -v /opt:/opt quay.io/joukou/flannel-build`

`/opt/bin/flanneld` is now installed.

For CoreOS deployments it may be easier to use a pre-built binary; e.g.,

`wget https://github.com/joukou/joukou-docker-flannel-build/releases/download/git%2B9c63c4e/flanneld`

## Contributors

* [Isaac Johnston](https://github.com/superstructor) ([Joukou Ltd](https://joukou.com))

## License

Copyright &copy; 2014 Joukou Ltd.

Build Flannel in a Docker Container is under the Apache 2.0 license. See the
[LICENSE](LICENSE) file for details.
