Build Flannel in a Docker Container
===================================

This is NOT an official build, once the [Flannel project](https://github.com/coreos/flannel) has binary releases this repository will likely be deleted.

## Usage

`docker -v /opt:/opt quay.io/joukou/flannel-build`

`/opt/bin/flanneld` is now installed.

For CoreOS deployments it may be easier to use a pre-built binary; e.g.,

`wget https://github.com/joukou/joukou-docker-flannel-build/releases/download/v0.1.0/flanneld-linux-amd64`

## Contributors

* [Isaac Johnston](https://github.com/superstructor) ([Joukou Ltd](https://joukou.com))

## License

Copyright &copy; 2014 Joukou Ltd.

Build Flannel in a Docker Container is under the Apache 2.0 license. See the
[LICENSE](LICENSE) file for details.
