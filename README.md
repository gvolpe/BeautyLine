# BeautyLine

This repository contains a copy of [BeautyLine](https://www.gnome-look.org/p/1425426/), which source does not seem to be published anywhere else.

In addition, it contains a customized version of it that adds status icons for WiFi, Bluetooth and Volume control. I performed this customization and I am currently using this theme in my [NixOS](https://github.com/gvolpe/nix-config) machine.

You should be able to find this soon on Nixpkgs unstable under the attribute name `beauty-line-icon-theme`.

### Troubleshooting

In most versions, there is a badly named file that causes the following error.

```shell
gtk-update-icon-cache: The generated cache was invalid.
```

Renaming it should fix the issue.

```shell
$ mv apps/scalable/goa-account-msn.svg\n.svg apps/scalable/goa-account-msn.svg
```
