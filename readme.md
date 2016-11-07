# angular2-bundle
[![Dependency Status](https://david-dm.org/blacksonic/angular2-bundle.svg)](https://david-dm.org/blacksonic/angular2-bundle)
[![devDependency Status](https://david-dm.org/blacksonic/angular2-bundle/dev-status.svg)](https://david-dm.org/blacksonic/angular2-bundle?type=dev)

Dependency bundle for all the Angular 2 related packages.
It aims to reduce the package number.

Instead of this
```
"dependencies": {
  "@angular/common": "^2.1.2",
  "@angular/compiler": "^2.1.2",
  "@angular/compiler-cli": "^2.1.2",
  "@angular/core": "^2.1.2",
  "@angular/forms": "^2.1.2",
  "@angular/http": "^2.1.2",
  "@angular/platform-browser": "^2.1.2",
  "@angular/platform-browser-dynamic": "^2.1.2",
  "@angular/platform-server": "^2.1.2",
  "@angular/router": "^3.1.2",
  "core-js": "^2.4.1",
  "rxjs": "^5.0.0-beta.12",
  "zone.js": "^0.6.26"
}
```
you can write this
```
"dependencies": {
  "angular2-bundle": "2.1.2"
}
```

The package version is in sync with the version of ```@angular/core```.
Includes additional packages necessary to run an Angular 2 application.

### Installation

```
npm install angular2-bundle --save
```
