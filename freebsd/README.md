# Packages

## Repos
Switch to `latest` in `/etc/pkg/FreeBSD.confg`.

```
freebsd-update fetch
freebsd-update install
```

## GPU
In my case AMD RX570, so `polaris10` firmware.
```
drm-kmod
gpu-firmware-amd-kmod-polaris10
```

## Extra packages
```
git mc neovim neomutt nano devcpu-data
```
