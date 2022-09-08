# Animate On Scroll 
## ⚙ Installation

### Basic

Add styles in `<head>`:

```html
  <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
```

Add script right before closing `</body>` tag, and initialize AOS:
```html
  <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>
```

### Using package managers

Install `aos` package:
* `yarn add aos@next`
* or `npm install --save aos@next`

Import script, styles and initialize AOS:
```js
import AOS from 'aos';
import 'aos/dist/aos.css'; // You can also use <link> for styles
// ..
AOS.init();
```

In order to make it work you'll have to make sure your build process has configured styles loader, and bundles it all correctly.
If you're using [Parcel](https://parceljs.org/) however, it will work out of the box as provided.


