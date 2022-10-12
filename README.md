# blog

## SSH

```bash
eval $(ssh-agent) && ssh-add ~/.ssh/id_rsa
```

```bash
eval $(keychain --eval --agents ssh id_rsa)
```

```bash
ssh-agent bash
```

## CPU

### Disable HT

```bash
echo off > /sys/devices/system/cpu/smt/control
```

## Linux

### CentOS8 stream

```bash
dnf --disablerepo '*' --enablerepo=extras swap centos-linux-repos centos-stream-repos
dnf distro-sync
```

## Kubernetes

### Docs CRDs

<https://doc.crds.dev/>
