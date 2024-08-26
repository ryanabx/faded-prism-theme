# Exporting zed theme

```shell
git clone https://github.com/zed-industries/zed.git
cd crates/theme_importer
cargo run -p theme_importer -- <THEME_PATH> --output <OUTPUT_PATH>
# Put output in the theme-family.json in themes: [{...}]
```