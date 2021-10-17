# Lolcate wrapper for Ulauncher

Extension for [ulauncher](https://ulauncher.io/) to visit your files anytime, anywhere.

This is "fork" of [ulauncher-searchfile extension](https://github.com/compilelife/ulauncher-searchfile) which is not maintained anymore.

## Dependencies

### lolcate
- [`lolcate`](https://github.com/ngirard/lolcate-rs) is alternative to `locate`. (Note that it's lo**l**cate not locate)
- fast, configurable indexing tool
- lolcate configuration is topic for official documentation, please [head there](https://github.com/ngirard/lolcate-rs#guide) if you need help with config

## Usage 

All aguments are passed to `lolcate`, which accepts plain text, but also regexes.

Press Alt+Number/Enter to open files using `xdg-open`.

Alternative, you can press Alt-Enter to switch to copy-to-clipboard menu.

### Limitations
- Only default database is used
- No way to reach results which did not fit into result list (depends on limit settings)
