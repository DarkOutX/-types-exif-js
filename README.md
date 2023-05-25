# @types/exif-js

This is a package to extend type declaration of [exif-js](https://www.npmjs.com/package/exif-js)

You can find declaration of especially EXIF-tags [here](./ExifData.d.ts)

## Installation | Warning
Currently I didn't find a solution to override original d.ts file from _node_modules/exif-js/exif.d.ts_
So I know just 2 possible ways:
 - Rename `node_modules/exif-js/exif.d.ts` to `node_modules/exif-js/exif._d.ts`
 - Put this project in root of your project and modify tsconfig.json with 
    ```
    HEE
   ```

## Contributions
This is an [open source project](LICENSE.md). Please contribute by forking this repo and issueing a pull request.

You can also contribute by [filing bugs or new features please issue](/-types-exif-js/issues).
Or improve the documentation.
