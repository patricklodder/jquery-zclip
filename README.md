jquery-zclip
============

jQuery ZeroClipboard

Copyright 2011, SteamDev

Originally forked from: http://steamdev.com/zclip

Released under the MIT license, see [LICENSE](LICENSE).

### Usage

```javascript
jQuery({selector}).zclip({options});
```

- ```selector```: any valid jquery object selector
- ```options```: Object, see section below.


### Options

Option        | Default value             | Description
------------- | ------------------------- | ------------
path          | ```'ZeroClipboard.swf'``` | The path to ZeroClipboard.swf
copy          | ```null```                | String to copy or function that returns a string to copy
afterCopy     | ```null```                | Function to execute after copying
beforeCopy    | ```null```                | Function to execute before copying
clickAfter    | ```true```                | Relay a click event to the element bound to after copying
setHandCursor | ```true```                | Set the cursor to pointer
setCSSEffects | ```true```                | Add ```hover``` and ```active``` classes to the element bound to 

NOTE: Since v1.1.5, default options can be set globally by setting the value of ```ZeroclipBoard.defaults.{option}```.
