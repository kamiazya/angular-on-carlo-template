# Angular on carlo

## What's this?

A demo of turning [Angular](https://github.com/angular/angular)'s project into a desktop application by using [carlo](https://github.com/GoogleChromeLabs/carlo).

## How to use?

Running the `yarn start` command will build the Angular project and run the carlo process.

```bash
$ yarn start
 yarn run v1.12.3
 $ run-s build start:carlo
 $ ng build --prod

 Compiling @angular/core : es2015 as esm2015

 Compiling @angular/common : es2015 as esm2015

 Compiling @angular/platform-browser : es2015 as esm2015

 Compiling @angular/platform-browser-dynamic : es2015 as esm2015

 Compiling @angular/router : es2015 as esm2015
 Date: 2019-06-08T16:17:14.310Z
 Hash: 8f396cdc46e97facd68e
 Time: 25745ms
 chunk {0} runtime-es2015.858f8dd898b75fe86926.js (runtime) 1.41 kB [entry]  [rendered]
 chunk {1} main-es2015.2e78c961ce65969fc656.js (main) 207 kB [initial] [rendered]
 chunk {2} polyfills-es2015.559e7c8b3a629fdb5581.js (polyfills) 36.8 kB [initial]  [rendered]
 chunk {3} styles.09e2c710755c8867a460.css (styles) 0 bytes [initial] [rendered]
 $ ts-node --project carlo/tsconfig.json carlo/main.ts
 ✨  Done in 32.41s.
```

The Angular app launches as a desktop app, as shown in the image below.

![Schreenshot](./media/AngularOnCarlo.png)

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Author

[kamiazya(Yuki Yamazaki)](https://github.com/kamiazya)

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W5VDNO)
