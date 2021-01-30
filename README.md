# WACOMGSS-NPM


First stage sdk js migration from wacom to npm, currently only wgssStuSdk.js has been migrated, to use import the library as follows

```
import WacomGSS from "wacomgss-npm";
```

Do not use encryption, as it presents errors that must be fixed,
load the js files shown in the examples from the index.html, to access the functions of these js files, for example: q.js, they must access from the window object properties for example: window ['q'], These js files will be included in the library soon

## Documentation:

https://developer-docs.wacom.com/stu/docs/sigcaptx-getting-started

## Examples:

https://developer-docs.wacom.com/stu/docs/sigcaptx-guide#23-javascript-sdk-framework

