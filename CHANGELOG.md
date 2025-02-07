# Changelog

## \[0.2.2]

- [`bbd3ffb`](https://www.github.com/tauri-apps/global-hotkey/commit/bbd3ffbea2a76eaae7cd344a019a942456f94a26)([#23](https://www.github.com/tauri-apps/global-hotkey/pull/23)) Generate a hash-based id for hotkeys. Previously each hotkey had a unique id which is not necessary given that only one hotkey with the same combination can be used at a time.

## \[0.2.1]

- [`b503530`](https://www.github.com/tauri-apps/global-hotkey/commit/b503530eb49a7fe8da3e49080e3f72f82a70b7a2)([#20](https://www.github.com/tauri-apps/global-hotkey/pull/20)) Make `GlobalHotKeyManager` Send + Sync on macOS.

## \[0.2.0]

- Support more variants for `HotKey::from_str` and support case-insensitive htokey.
  - [25cbda5](https://www.github.com/tauri-apps/global-hotkey/commit/25cbda58c503b8230af00c6192e87d5ce1fc2742) feat: add more variants and case-insensitive hotkey parsing ([#19](https://www.github.com/tauri-apps/global-hotkey/pull/19)) on 2023-04-19

## \[0.1.2]

- On Windows, fix registering htokeys failing all the time.
  - [65d1f6d](https://www.github.com/tauri-apps/global-hotkey/commit/65d1f6dffd54bafe46d1ae776639b5dd10e78b96) fix(window): correctly check error result on 2023-02-13
- Fix crash on wayland, and emit a warning instead.
  - [4c08d82](https://www.github.com/tauri-apps/global-hotkey/commit/4c08d82fa4a20c82988b49f718688ec29de8a781) fix: emit error on non x11 window systems on 2023-02-13

## \[0.1.1]

- Update docs
  - [6409e5d](https://www.github.com/tauri-apps/global-hotkey/commit/6409e5dd351e1cae808c0042f4507e9afad70a05) docs: update docs on 2023-02-08

## \[0.1.0]

- Initial Release.
  - [72873f6](https://www.github.com/tauri-apps/global-hotkey/commit/72873f629b47565888d5f2a4264476c9974686b6) chore: add initial release change file on 2023-01-16
  - [d0f1d9c](https://www.github.com/tauri-apps/global-hotkey/commit/d0f1d9c58eba60015f658f7a742c200c2d1bd55e) chore: adjust change file on 2023-01-16
