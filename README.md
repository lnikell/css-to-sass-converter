# CSS to SASS and Stylus converter for Sublime Text 3

[![Join the chat at https://gitter.im/lnikell/css-converter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/lnikell/css-converter?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
**STOP WASTING YOUR TIME** removing brackets, semicolons and formating any css inserted from your browser to Sublime Text.

![Example usage]
(https://habrastorage.org/files/1cc/aa6/0bb/1ccaa60bb0924c8b8976b99acf0e5fd9.gif)

You could also copy something like this:
```css
{
  display: block;
  color: #ffffff;
}
```
And plugin will transform it to:
```css
display: block
color: #ffffff
```

## Features
- works without any gems or npm packages
- supports nested selectors
- unprefixing (comming soon)

## Installation
### via Package Control
- Open the Command Pallete (ctrl+shift+P or cmd+shift+P);
- Type "Install Package"
- Type "css to sass converter" and hit return.

## Configuration options

### colon
**Default**: `true`.
Add semicolon after property name or not. Makes sense only for stylus.

## Default key bindings

`Ctrl+V` on Windows/Linux

`Cmd+V` on OS X
