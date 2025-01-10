# winit - Cross-platform window creation and management in Rust

Unofficial fork adding support for wayland layer-shell protocol. This fork
is mainly a backport of [#4044](https://github.com/rust-windowing/winit/pull/4044) to v0.30, but has additional changes that may make it **not compile on all platforms**.
Compilation and runtime **is not tested on non-wayland platforms**.

```toml
[dependencies]
winit = { git = "https://github.com/danbulant/winit", branch="ls_release" }
```

Support, backporting of other features and bugfixes are not guaranteed.
