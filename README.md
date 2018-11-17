# wlstream

Records and streams.

## Installation
```
build meson
ninja -C build
sudo ninja -C build install
```

### Usage
```
wlstream  <source id> <hardware device type> <device> <encoder name> <pixel format> <bitrate in Mbps> <file path>
```
### Example
```
wlstream 24 vaapi /dev/dri/renderD128 libx264 nv12 12 output.mkv
```
