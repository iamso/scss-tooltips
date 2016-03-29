SCSS Tooltips
=============

This is a simple SCSS Tooltip Library, no Javascript needed.

To avoid the standard title behavior, it uses the attribute `data-title`.

How it works
------------
#### HTML/CSS
Download the repository and check out the source code of the demo.

#### SCSS
If you use SCSS, there's an easy way to create customized tooltips. Just change the variables in the `_variables.scss` file.

```scss
// Tooltip variables
//
$tooltip-bg: rgba(0,0,0,0.8);
$tooltip-color: #fff;
$tooltip-font-size: 0.9em;
$tooltip-box-shadow: none;

$tooltip-arrow-length: 0.5em;
$tooltip-arrow-width: 0.5em;
$tooltip-arrow-distance: 0;

$tooltip-side-margin: 1.7em;

$tooltip-border-radius: 0;
$tooltip-padding-horizontal: 1.4em;
$tooltip-padding-vertical: 0.6em;

$tooltip-movement: 0.6em;
$tooltip-margin-animation: 0.4s;
$tooltip-opacity-animation: 0.4s;
$tooltip-margin-delay: 0s;
$tooltip-opacity-delay: 0s;
$tooltip-margin-easing: $easeOutExpo;
$tooltip-opacity-easing: $easeOutExpo;
```

Check out `combined.scss` for more details.

License
-------
MIT License

---

Copyright © 2016 Steve Ottoz
