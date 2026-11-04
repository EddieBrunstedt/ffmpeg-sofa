# ffmpeg-sofa

Arch Linux's [ffmpeg](https://gitlab.archlinux.org/archlinux/packaging/packages/ffmpeg)
package, unchanged except that it is built with libmysofa. That enables
FFmpeg's `sofalizer` filter: HRTF-based binaural audio from SOFA (Spatially
Oriented Format for Acoustics) files.

It provides and conflicts with `ffmpeg`, so installing it swaps out the
official package and everything that depends on `ffmpeg` keeps working.

## Build and install

```bash
makepkg -si
```
