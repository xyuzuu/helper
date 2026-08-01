## Helper Functions

> A collection of upload and shortener functions ready to use.

> [!NOTE] 
> Rhe original code from [@neoxr/helper](https://npmjs.com/@neoxr/helper)

<p align="center">

[![npm version](https://badgen.net/npm/v/@xyuzuu/helper)](https://badgen.net/npm/v/express) [![Npm package monthly downloads](https://badgen.net/npm/dm/@xyuzuu/helper)](https://npmjs.com/package/@xyuzuu/helper) ![GitHub repo size](https://img.shields.io/github/repo-size/xyuzuu/helper?style=flat) ![Types](https://badgen.net/npm/types/@xyuzuu/helper)

</p>

### 1. Open's API (Neoxr)

```js
import { short, upload } from '@xyuzuu/helper'

/**
 * Uploads a file from a Buffer or a remote file URL.
 * @param input Buffer (binary file) or string (URL)
 * @param filename String (filename) - optional
 * @param extension String (extension) - optional
 * @returns Promise<Response>
 * Information : support all extension
 */
upload(input: Buffer | String, filename?: String, extension?: string).then(console.log)

/**
 * Shortens a given URL.
 * @param {string} url - The full URL to shorten.
 * @returns {Promise<string>} A promise that resolves to the shortened URL.
 */
short(input: String).then(console.log)
```
**Site :** [https://s.neoxr.eu](https://s.neoxr.eu)

### 2. TmpFiles

```js
import { tmpfiles } from '@xyuzuu/helper'

/**
 * Uploads a file from a Buffer or a remote file URL.
 * @param input Buffer (binary file) or string (URL)
 * @param filename String (filename) - optional
 * @param extension String (extension) - optional
 * @returns Promise<Response>
 * Information : support all extension exclude (.js)
 */
tmpfiles(input: Buffer | String, filename?: String, extension?: String).then(console.log)
```
**Site :** [https://tmpfiles.org](https://tmpfiles.org)

### 3. ImgBB

```js
import { imgbb } from '@xyuzuu/helper'

/**
 * Uploads a file from a Buffer or a remote image URL.
 * @param input Buffer (binary file) or string (URL)
 * @returns Promise<Response>
 * Information : image only
 */
imgbb(input: Buffer | String).then(console.log)
```
**Site :** [https://imgbb.com](https://imgbb.com)

### 4. ImgKub

```js
import { imgkub } from '@xyuzuu/helper'

/**
 * Uploads a file from a Buffer or a remote image URL.
 * @param input Buffer (binary file) or string (URL)
 * @returns Promise<Response>
 * Information : image only
 */
imgkub(input: Buffer | String).then(console.log)
```
**Site :** [https://imgkub.com](https://imgkub.com)

### 5. Uguu

```js
import { uguu } from '@xyuzuu/helper'

/**
 * Uploads a file from a Buffer or a remote file URL.
 * @param input Buffer (binary file) or string (URL)
 * @param filename String (filename) - optional
 * @param extension String (extension) - optional
 * @returns Promise<Response>
 * Information : support all extension
 */
uguu(input: Buffer | String, filename?: String, extension?: String).then(console.log)
```
**Site :** [https://uguu.se](https://uguu.se)

### 6. Catbox

```js
import { catbox } from '@xyuzuu/helper'

/**
 * Uploads a file from a Buffer or a remote file URL.
 * @param input Buffer (binary file) or string (URL)
 * @param filename String (filename) - optional
 * @param extension String (extension) - optional
 * @returns Promise<Response>
 * Information : support all extension
 */
catbox(input: Buffer | String, filename?: String, extension?: String).then(console.log)
```
**Site :** [https://catbox.moe](https://catbox.moe)

### 7. Studio Inter Media

```js
import { studiointermedia } from '@xyuzuu/helper'

/**
 * Uploads a file from a Buffer or a remote image URL.
 * @param input Buffer (binary file) or string (URL)
 * @returns Promise<Response>
 * Information : image only
 */
studiointermedia(input: Buffer | String).then(console.log)
```
**Site :** [https://www.studiointermedia.com/](https://www.studiointermedia.com/)

### 8. Quax

```js
import { quax } from '@xyuzuu/helper'

/**
 * Uploads a file from a Buffer or a remote file URL.
 * @param input Buffer (binary file) or string (URL)
 * @param filename String (filename) - optional
 * @param extension String (extension) - optional
 * @returns Promise<Response>
 * Information : support all extension exclude (.ogg)
 */
quax(input: Buffer | String, filename?: String, extension?: String).then(console.log)
```
**Site :** [https://qu.ax](https://qu.ax)

### 9. Crypty CDN

```js
import { crypty } from '@xyuzuu/helper'

/**
 * Uploads a file from a Buffer or a remote file URL.
 * @param input Buffer (binary file) or string (URL)
 * @param filename String (filename) - optional
 * @param extension String (extension) - optional
 * @returns Promise<Response>
 * Information : support all extension
 */
crypty(input: Buffer | String, filename?: String, extension?: String).then(console.log)
```
**Site :** [https://cryptybyte.pages.dev](https://cryptybyte.pages.dev)

### 10. Temp Image

```js
import { tempimage } from '@xyuzuu/helper'

/**
 * Uploads a file from a Buffer or a remote image URL.
 * @param input Buffer (binary file) or string (URL)
 * @returns Promise<Response>
 * Information : image only
 */
tempimage(input: Buffer | String).then(console.log)
```
**Site :** [https://www.temp-image.com/](https://www.temp-image.com/)

### 11. X0

```js
import { x0 } from '@xyuzuu/helper'

/**
 * Uploads a file from a Buffer or a remote file URL.
 * @param input Buffer (binary file) or string (URL)
 * @param filename String (filename) - optional
 * @param extension String (extension) - optional
 * @returns Promise<Response>
 * Information : support all extension
 */
x0(input: Buffer | String, filename?: String, extension?: String).then(console.log)
```
**Site :** [https://x0.at](https://x0.at)

### 12. Pixhost

```js
import { pixhost } from '@xyuzuu/helper'

/**
 * Uploads an image from a Buffer or a remote image URL.
 * @param input Buffer (binary image) or string (URL)
 * @param filename String (filename) - optional
 * @returns Promise<Response>
 * Information : image only
 */
pixhost(input: Buffer | String, filename?: String).then(console.log)
```
**Site :** [https://pixhost.to](https://pixhost.to)

### 13. 8upload

```js
import { eightupload } from '@xyuzuu/helper'

/**
 * Uploads an image from a Buffer or a remote image URL.
 * @param input Buffer (binary image) or string (URL)
 * @param filename String (filename) - optional
 * @returns Promise<Response>
 * Information : image only
 */
eightupload(input: Buffer | String, filename?: String).then(console.log)
```
**Site :** [https://8upload.com](https://8upload.com)