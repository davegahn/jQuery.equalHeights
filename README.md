# jQuery Equal Heights by row
Version 1.0.0

This plugin makes the height of all selected elements exactly equal.

## Authors

iBird Rose ([vk.com](https://vk.com/iiibird)) & KFan ([vk.com](https://vk.com/gildarb))

## Manual Download - Stable Release
[Download](https://github.com/iiiBird/jQuery.equalHeights/releases)

## Install
Include jquery.equalheights.js after calling jQuery.
```
<script src="jquery.equalheights.js" type="text/javascript"></script>
```

## Usage
```
$(function() {
    $(".item").equalHeights(options);
});
```

## Options
The default options are:
```
{
  innerItem: false,
  parent: $(this).parent(),
  byRow: true
}

```
Where:
* innerItem - Inner element that you want to set the height. type - string. (Example: innerItem: ".item_content",)
* parent - Parent element if a direct parent is not needed element. type - object (Example: parent: $(".parent"),)
* byRow - true or false to enable row detection.

more information and examples in [demo](https://iiibird.github.io/jQuery.equalHeights/demo/)

## Demo and Examples
[Examples](https://iiibird.github.io/jQuery.equalHeights/demo/)

## Changelog

__Version 1.0.0__

* First Release
