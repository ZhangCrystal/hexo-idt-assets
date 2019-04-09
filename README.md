# hexo-asset-images


Give asset the local file a absolutely path automatically,Such as pictures, TXT files, PDF and so on.

# Usege

```shell
npm install hexo-idt-assets --save
```

# Example

```shell
hello
├── hello.jpg
└── text.txt

hello.md
```

Make sure `post_asset_folder: true` in your `_config.yml`.

Just use `[介绍](path/hello.jpg)` to insert `hello.jpg`.
