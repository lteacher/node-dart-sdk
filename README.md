### About
This is just the [DDC][ddc] compiled dart sdk so that it can be included in some package json. It won't be up to date and is just for experimentation only.

**Example `package.json`**

```json
{
  "name": "some-cool-name",
  "devDependencies": {
    "dart_sdk": "lteacher/node-dart-sdk"
  }
}

```

*Probably you would have some other stuffs but this will get the `dart_sdk` into the node modules for you so your compiled dart modules will work*

[ddc]:[https://github.com/dart-lang/sdk/tree/master/pkg/dev_compiler]or
