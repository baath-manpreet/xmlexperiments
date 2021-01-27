# Changelog - UsefulViews

[![Releases](https://img.shields.io/badge/LabelledSpinner-releases-blue.svg)](https://github.com/FarbodSalamat-Zadeh/UsefulViews/releases)
[![Tags](https://img.shields.io/badge/LabelledSpinner-tags-FF69B4.svg)](https://github.com/FarbodSalamat-Zadeh/UsefulViews/tags)

## 2.3.6
_18th Jun '16_
- Update Android Support library dependencies to 24.0.0
- Update SDK versions (compileSdkVersion and targetSdkVersion) to 24 (including in `.travis.yml`)

## 2.3.4 - .5
_12th Jun '16_
- Add `mAnimate` boolean field for `FlippableView` to decide whether to animate

## 2.3.3
_11th Jun '16_
- Add the option to animate `flip()`
- Add `getViewFlipper()` which returns the `ViewFlipper` associated with the `FlippableView`

## 2.3.2
_9th Jun '16_
- Make `flip()` method of `FlippableView` public
- Update Gradle tools project dependency to 2.1.0
- Update Android Support library dependencies to 23.4.0

## 2.3.1
_13th Apr '16_
- Rename attribute `entries` of `LabelledSpinner` to resolve conflicts with other libraries

## 2.3
_8th Apr '16_
- Update Gradle tools project dependency to 2.0.0
- Update Android Support library dependencies to 23.3.0

## 2.2
_31st Mar '16_
- Update Gradle tools project dependency to 2.0.0-rc1
- Fix typo in project `.gitignore` file

## 2.1.3 - .4
_28th Mar '16_
- Fixes issue where `FlippableView` could not be flipped after being update

## 2.1.2
_28th Mar '16_
- Adds option for `FlippableView` to remove both front and back Views

## 2.1.1
_28th Mar '16
- Fixes issue with `FlippableView` not being available

## 2.1
_28th Mar '16_
- Adds the `FlippableView` widget

## 2.0.1
_27th Mar '16_
- Fixes issue regarding Javadoc checks when uploading to Bintray

## 2.0
_27th Mar '16_
- Changes library name from _LabelledSpinner_ to _UsefulViews_
- Refactoring so that package `com.farbod.labelledspinner` is moved to `com.satsuware.usefulviews` (reasons for this are explained in the commit descriptions)
- Library descriptions and dependencies updated accordingly

## 1.2.0
_17th Mar '16_
- Pushes missing updates from the library to Bintray hence fixing an issue (#28) where calling `LabelledSpinner` constructors gave an error
- Updates Android Support libraries to version 23.2.1

## 1.1.5
_30th Jan '16_
- Include update to Android build tools (23.0.2)
- Fix `LabelledSpinner` constructor calls (where there were calls to the View constructor for API 21+)

## 1.1.4
_17th Jan '16_
- Add optional error text for when the first item (e.g. a prompt text)of the `LabelledSpinner` is selected

## 1.1.3
_10th Jan '16_
- Travis CI integration
- Change library used to upload to Bintray

## 1.1.2
_5th Jan '16_
- The items displayed can be set using an XML attribute. Also, `setItemsArray` can now have a `CharSequence[]` as the argument.
- `LabelledSpinner` has new constructors (including one for API 21+)
- Refactoring of `LabelledSpinner` (including the use of `List` instead of `ArrayList`)
- Optimised imports

## 1.1
_28th Dec '15_
- Cleared up lots of minor issues.

## Initial release (1.0)
_24th Dec '15_
- Initial release of the library, transferred originally from a number of files on GitHub Gist.
