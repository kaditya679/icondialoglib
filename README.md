# Icon picker dialog
A fully customizable icon picker dialog that provides easy access to quality icons without having to include them in your probject. Icons used by this library are nearly all part of the [Material Design Icons](https://github.com/Templarian/MaterialDesign) set, made by Google as well as several contributors. The picker include a default set of 1,045 icons as of 2.2.0 but custom icons can be added. Additional icons released on MDI may also be included in future versions.

All icons are SVG files from which only the path was kept, which allow for a very small size. Adding this library to your app should result in a 350kB total increase in size: ~140kB from the icons, ~30kB from each language of the labels and 60kB from the code itself. For comparison, if vector drawable files were used instead of only paths, the size only for the icons would be over 400kB. Performance should not be a problem on most phones as drawables are cached.

### Gradle dependency
`compile 'com.maltaisn:icondialog:X.Y.Z'`

Replace `X.Y.Z` with lastest version number: [ ![Download](https://api.bintray.com/packages/maltaisn/icon-dialog/icon-dialog/images/download.svg) ](https://bintray.com/maltaisn/icon-dialog/icon-dialog/_latestVersion)

If you haven't migrated to AndroidX, use version 2.0.2. Versions 2.1.0 and up use AndroidX. Minimum API is 19.

## Tutorial
All documentation and examples on usage and customization available on [the wiki](https://github.com/maltaisn/icondialoglib/wiki).

## Screenshots
<img src="screenshots/demo.gif" alt="Demo" width="400px"/>

## Changelog
View [changelog](https://github.com/maltaisn/icondialoglib/blob/master/CHANGELOG.md) for release notes

## Licenses
- Library - Apache License 2.0
- Material Design Icons - SIL Open Font License 1.1
- Google Material Design Icons - Apache License 2.0
- Other icons - Apache License 2.0

## Translations
This library is available in English, French, Portuguese, German and Spanish. If you make a translation please send a pull request. Translating the whole library actually takes between 3 to 5 hours (over 1,000 labels not counting aliases). A collection of images with the icons for each label can be downloaded [here](https://github.com/maltaisn/icondialoglib/files/2957686/label-images.zip) and can be very useful when translating. For more information, visit the wiki page [Translating](https://github.com/maltaisn/icondialoglib/wiki/Translating).