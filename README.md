# packer-vsphere-ubuntu.20.04

[Packer][] template for building Ubuntu 20.04 LTS (Focal Fossa) on vSphere infrastructure. Based on Nick Charlton's article [_Automating Ubuntu 20.04 installs with Packer_][1].

## Usage

```sh
packer build ubuntu-2004.json
```

[Packer]: https://packer.io
[1]: https://www.debian.org/devel/debian-installer/
[2]: https://github.com/CanonicalLtd/subiquity
[3]: https://nickcharlton.net/posts/automating-ubuntu-2004-installs-with-packer.html
