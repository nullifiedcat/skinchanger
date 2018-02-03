# Basic skinchanger

This is a basic skinchanger for TF2.

# Building

```
cmake .
make
```

# Usage

```
sudo ./skinchanger `pidof hl2_linux`
```

# Custom skins

Create a file named "user.json" in folder "data" and put your skin settings there. If skinchanger can't find/load file "user.json", it'll load "nullifiedcat.json" by default.

# Credits

Blackfire

# TF2 Updates

This skinchanger will break with each TF2 update because sigscanning is not included in this release.