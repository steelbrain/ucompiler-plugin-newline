# UCompiler-Plugin-NewLine

This plugin for ucompiler makes sure that your generated files always end with
a new line. It also normalizes their EOLs to LF.

## How to Use

You first need to add `ucompiler-plugin-newline` to your `devDependencies`
within your `package.json`, then simply add "newline" to the `plugins` field
in your `.ucompilerrc` configuration file.

```js
{
  plugins: ["newline"]
}
```

## License

This project is licensed under the terms of MIT License
