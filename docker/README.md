# Install

Refer:
`https://github.com/docker/docker-install`
`https://docs.docker.com/engine/install/debian/`

## Usage:

From `https://get.docker.com`:
```shell
curl -fsSL https://get.docker.com -o get-docker.sh
sh get-docker.sh

sudo apt-get install -y uidmap
dockerd-rootless-setuptool.sh install
```

From `https://test.docker.com`:
```shell
curl -fsSL https://test.docker.com -o test-docker.sh
sh test-docker.sh
```

From the source repo (This will install latest from the `stable` channel):
```shell
sh install.sh
```

## Testing:

To verify that the install script works amongst the supported operating systems run:

```shell
make shellcheck
```

