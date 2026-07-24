# saver-glyphs

Official **glyphs** visualizer plugin for [IdleScreen](https://github.com/idlescreen/idle).

## Build

Requires the idle engine checked out into `./idle` for `idle-api` path deps:

```bash
git clone https://github.com/idlescreen/idle-saver-glyphs.git
cd idle-saver-glyphs
git clone https://github.com/idlescreen/idle.git idle
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
