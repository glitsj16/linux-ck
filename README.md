Build [linux-ck](https://aur.archlinux.org/packages/linux-ck) kernel and headers via GitHub Action.

See https://github.com/glitsj16/pkgbuild-action for details.


**IMPORTANT**

The AUR package currently [fails](https://github.com/graysky2/linux-patches/commit/f6a7d5ea0cbb04b6a00caee62ece1d76270ea922#commitcomment-102059146) to build kernel 6.2.x due to issues with [rebasing the ck-hrtimer patches](https://github.com/graysky2/linux-patches/commit/f6a7d5ea0cbb04b6a00caee62ece1d76270ea922).
We use a slightly [modified]() patch to fix this for lab16.
