<div align="center">
    <img src="https://imagineer.in/assets/img/posts/packer-ubuntu.png" alt="logo" width="350px" style="margin-top: 1em">
    <h1>Packer for Ubuntu server</h1>
    <h4>Packer config to build VMware virtual machines (VMX) and VirtualBox machines (OVF) from Ubuntu 20.04 server ISO file as a source.</h4>
</div><br>

## Ubuntu 20.04 Server (VMWare)

Run packer build:

```bash
$ packer build -on-error=ask -force ubuntu-20.04-live-server-packer.json
```


## Ubuntu 20.04 Legacy Server (VMWare)

Run packer build:
```bash
$ packer build -on-error=ask -force ubuntu-20.04-legacy-server-packer.json
```
<br>

For more info: [imagineer.in/blog/packer-build-for-ubuntu-20-04](https://imagineer.in/blog/packer-build-for-ubuntu-20-04/)


## Ubuntu 20.04 Server (VirtualBox)
packer version 1.6.5

Run packer build:

```bash
$ packer build -on-error=ask -force ubuntu-20.04-live-server-packer-virtualbox.json
```

## Ubuntu 20.04 Legacy Server (VirtualBox)
packer version 1.6.5

Run packer build:

```bash
$ packer build -on-error=ask -force ubuntu-20.04-legacy-server-packer-virtualbox.json
```

## Ubuntu 20.04 Server with Java and Jenkins (VirtualBox)
packer version 1.6.5

Run packer build:

```bash
$ packer build -on-error=ask -force ubuntu-20.04-live-server-packer-virtualbox-jenkins.json
```
