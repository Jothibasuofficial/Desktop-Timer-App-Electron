# Desktop Timer Application

Build a native desktop timer app with Angular and Electron.

![TimerApp](/demo/demo.gif)

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Basic Usage

git clone<br/>
<code>cd</code> Desktop-Timer-App-Electron<br/>
npm install

## Build

* Run `npm run electron-build` to build the project

* ### Runnable on the following host platforms:
        - Windows (32/64 bit)
        - macOS (formerly known as OS X)
        - Linux (x86/x86_64)
        
* ### To get desktop app run the following:
        electron-packager <sourcedir> <appname> --platform=<platform> --arch=<arch> [optional flags...]
         
This will:
* Find or download the correct release of Electron

* Use that version of Electron to create a app in `<out>/<appname>-<platform>-<arch>` (this can be customized via an optional flag)
`--platform` and `--arch` can be omitted, in two cases:

* If you specify `--all` instead, bundles for all valid combinations of target platforms/architectures will be created.

* Otherwise, a single bundle for the host platform/architecture will be created.

## Further References

*   [Electron Installation](https://electronjs.org/docs/tutorial/installation)

*   [Electron Packager](https://github.com/electron/electron-packager)

*   [Svg Round Progressbar](https://www.npmjs.com/package/angular-svg-round-progressbar)
