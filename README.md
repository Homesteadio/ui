Originally forked from `Decentrland` (Apache 2 license). Base is `semantic-ui-react` with themed overlay and custom components created by Decentraland.


View original story book: [ui.decentraland.org](https://ui.decentraland.org)

## Usage

Install it:

```bash
npm install --save homesteadio-ui
```

Import Homestead UI's styles in your App's entry point

```jsx
import 'homesteadio-ui/lib/styles.css'
```

Now you can use Homestead UI's components

```jsx
import React from 'react'
import { Button } from 'homesteadio-ui'

export class MyApp extends React.Component {
  render() {
    return <Button>Good Day</Button>
  }
}
```


## Alternative themes

You can use one of our alternative themes by importing in after Homestead UI's styles, like this:

```jsx
import 'homesteadio-ui/lib/styles.css'
import 'homesteadio-ui/lib/dark-theme.css'
```

Or you can create your own theme like this:

```css
/* my-theme.css */
:root {
  /* global */
  --background: #ffffff;
  --danger: #ffa900;
  --error: #ff0000;

  /* buttons */
  --primary: #ff2d55;
  --secondary: #f3f2f5;
  --primary-hover: #ff3d61;
  --secondary-hover: #ecebed;
  --secondary-on-modal: #f3f2f5;
  --secondary-on-modal-hover: #ecebed;

  /* text */
  --text: #16141a;
  --secondary-text: #676370;
  --text-on-primary: #ffffff;
  --text-on-secondary: #16141a;

  /* ui */
  --divider: #67637033;
  --dropdown: #ffffff;
  --dropdown-hover: #f3f2f5;
  --popup: #16141a;
  --popup-text: #ffffff;
  --navbar-popup: #ffffff;
  --navbar-popup-hover: #f3f2f5;
  --card: #ffffff;
  --outline: 1px solid #00000005;
  --modal: #ffffff;
  --dimmer: #ffffffdd;

  /* shadows */
  --shadow-1: 0px 2px 4px 0px rgba(0, 0, 0, 0.08);
  --shadow-2: 0px 10px 20px 0px rgba(0, 0, 0, 0.12);
  --shadow-3: 0px 16px 32px 0px rgba(0, 0, 0, 0.16);

  --shadow-color-1: 0px 2px 4px 0px rgba(0, 0, 0, 0.16);
  --shadow-color-2: 0px 10px 20px 0px rgba(0, 0, 0, 0.2);
  --shadow-color-3: 0px 16px 32px 0px rgba(0, 0, 0, 0.24);

  /* svgs */
  --brightness: brightness(0.1); /* black svgs */
}
```

## Development

Install dependencies and start Storybook to make changes.

```
$ npm install
$ npm start
```

## License

We've continued using and make all available under Apache 2.0 License.

## In the spirit of good tidings
🎵 Home, home on the chain... where the winners HODL and make gains... 
