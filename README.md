# react-cornerstone-viewport

> Cornerstone medical image viewport component for React

[![NPM](https://img.shields.io/npm/v/react-cornerstone-viewport.svg)](https://www.npmjs.com/package/react-cornerstone-viewport)

Documentation and Examples: [https://react.cornerstonejs.org/](https://react.cornerstonejs.org/)

## Setup New Developer Environment (once only)
Open a terminal window and run this command:
```bash
npm install
npm adduser
```
You will need to log onto registry.npmjs.org and log in with your npm user account

## Publish updated package
1. Increment the version number in package.json
2. Then publish the new package uisng this command in a terminal window:

```bash
npm publish
```
3. Switch to your other project in VSCode (itxviewer2)
4. Open a command line.
5. type 'cd atx-frontend'
6. type 'npm install react-cornerstone-viewport-adrian' to get the new NPM package you just published.

You can check you have the latest version by looking for the correct version number for react-cornerstone-viewport-adrian in package.json

## Using in another project

```jsx
import React, { Component } from 'react'

import CornerstoneViewport from 'react-cornerstone-viewport-adrian'

class Example extends Component {
  render () {
    return (
      <CornerstoneViewport />
    )
  }
}
```

## License

MIT © [OHIF](https://github.com/OHIF)
