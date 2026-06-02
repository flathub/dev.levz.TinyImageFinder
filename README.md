# Tiny Image Finder 

___Image Finder with Preview___

This tool allows you to fast search and preview images from selected folder. It has scalable search algorithm that use all capabilities of your device. 

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub dev.levz.TinyImageFinder
flatpak run dev.levz.TinyImageFinder
```

## Building

```bash
git clone git@github.com:flathub/dev.levz.TinyImageFinder.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install dev.levz.TinyImageFinder.yml
```
