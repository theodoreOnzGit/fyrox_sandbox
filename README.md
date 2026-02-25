# fyrox\_sandbox
Journal for Learning about Fyrox, Rust Game engine


# first step 

Refer here:
```
https://fyrox-book.github.io/beginning/manual_installation.html#manual-installation
```
I used

```
cargo install fyrox-template
```

To start fyrox-template inside bash,
I added this into my bashrc file:

```
PATH=$PATH:$HOME/.cargo/bin
```

# running the editor 

```
cargo run --release --package editor
```

# 3d models 

Fyrox requires 3rd party software such as blender to use 

```
sudo pacman -S blender
```

However, in Arch Linux as of 25 feb 2026, there is an issue with 
python 3.14.
See issue here:
```
https://projects.blender.org/blender/blender/issues/152809
```

So Blender cannot export FBX files for Fyrox.

I used flatpak instead:

```
flatpak install org.blender.Blender
```

to run:


```
flatpak run org.blender.Blender
```
