# Timer

![Group 14](https://user-images.githubusercontent.com/31973579/150757360-90cca279-562f-45a8-980a-ddf4ffe844bf.png)

![Group 15](https://user-images.githubusercontent.com/31973579/150757450-cc52fd29-33f7-4e3c-812b-9a3584f43315.png)

![Group 16](https://user-images.githubusercontent.com/31973579/150757562-8810afda-2641-45d8-8c59-49091e7493aa.png)

![Group 17](https://user-images.githubusercontent.com/31973579/150757592-943e3cd0-c10e-428e-a52d-571766ff4dc3.png)

![Group 18](https://user-images.githubusercontent.com/31973579/150757607-43a5fdd2-f137-4913-bb20-a442909404bf.png)

![Group 19](https://user-images.githubusercontent.com/31973579/150757634-37822d97-b302-4286-8b60-b1a149c8ddaf.png)

# Features
- 7+ Themes.
- Fully Customizable.
- Touch Support.
- Modern UI.
- Javascript options.
- Custom callbacks.
- Fully Responsive.
- Cross-browser.
- Well documented.

# Installation

**For Commonjs & ESModules:**

```js
// in commonjs & ESModules
import Timer from "./Timer.js";
// or
// in commonjs
const Timer = require("./Timer.js");
```

**In Plain Javascript:**

```html
<!-- in html file -->
<head>
  ...
  <script src="./Timer.js"></script>
  ...
</head>
<body>
  ...
  <script type="text/javascript">
    // code
  </script>
</body>
```

# Use

```html
<!-- in html file -->
<head>
  ...
  <style>
    .container {
        background-color: black;
        width: 600px;
        height: 300px;
    }
  </style>
</head>
<body>
  <div class="container"></div>
  ...
</body>
```

```js
// in script tag or index.js file
const container = document.querySelectorAll(".container")[0];
//create timer
const timer12 = new Timer({
  target: container,
  format: "12-hrs",
  theme: "theme-bootstrap",
});
// track change
timer12.onChange(value => {
  console.log(value);
});
```

# Configuration

```typescript
{
  target: HTMLElement,  // required
  format: string,       // required
  theme: string,        // optional
  options: {            // optional
    labelColor: string,
    labelHours: string,
    labelMinutes: string,
    labelSeconds: string,
    labelAmPM: string,
    labelSize: string,
    labelWeight: string,
    separatorColor: string,
    backgroundColor: string,
    fontColor: string,
    focusFontColor: string,
    iconsColor: string,
    fontSize: string,
    fontWeight: string,
    ampmSize: string,
    ampmWeight: string
  }
}
```

## [Click Here to See Live Demo](https://sllujaan.github.io/Timer22/)🚀

