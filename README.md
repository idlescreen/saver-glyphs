# saver-glyphs

Official **glyphs** visualizer plugin for [IdleScreen](https://github.com/idlescreen/idle-core).

## Build

Requires a sibling checkout of the core daemon for `idle-api`:

```bash
git clone https://github.com/idlescreen/idle-core.git
git clone https://github.com/idlescreen/saver-glyphs.git
cd saver-glyphs
cargo build --release
```

## Install

After adding the IdleScreen package repository:

```bash
sudo apt install idle-saver-glyphs
# or: sudo dnf install idle-saver-glyphs
```

See [idlescreen.github.io/packages](https://idlescreen.github.io/packages/).

## License

Apache-2.0. See [LICENSE](LICENSE).
