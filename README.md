# @types/exif-js

This is a package to extend type declaration of [exif-js](https://www.npmjs.com/package/exif-js)

## Additional files
You can find declaration of especially EXIF-tags [here](./ExifData.d.ts)

Not all [tags](./tags.d.ts) are declared, but all mentioned

You can also find available string outputs for some tags [here](./strings.d.ts)

## Installation | Warning
Currently I didn't find a solution to override original d.ts file from _node_modules/exif-js/exif.d.ts_  
So I know just one possible way:
 - Rename `node_modules/exif-js/exif.d.ts` to `node_modules/exif-js/exif._d.ts`

## Contributions
This is an [open source project](LICENSE). Please contribute by forking this repo and issueing a pull request.

You can also contribute by [filing bugs or new features please issue](https://github.com/DarkOutX/-types-exif-js/issues).
Or improve the documentation.
