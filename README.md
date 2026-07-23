# plugin-glyphs

Official **glyphs** visualizer plugin for [IdleScreen](https://github.com/idlescreen/idlescreen).

## Build

Requires a sibling checkout of the core daemon for `trance-api`:

```bash
git clone https://github.com/idlescreen/idlescreen.git
git clone https://github.com/idlescreen/plugin-glyphs.git
cd plugin-glyphs
cargo build --release
```

## Install

After adding the IdleScreen package repository:

```bash
sudo apt install trance-plugin-glyphs
# or: sudo dnf install trance-plugin-glyphs
```

See [idlescreen.github.io/packages](https://idlescreen.github.io/packages/).

## License

Apache-2.0. See [LICENSE](LICENSE).
