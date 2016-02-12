# iOS Switcher
Switcher like iOS switch button in pure CSS.

This is a simple component that helps you make iOS style switches.

Supported by modern browsers: Chrome, Firefox, Safari, Opera, IE10+

![Preview](http://i.imgur.com/9GbHLuJ.jpg)

You can see the [demo here](https://htmlpreview.github.io/?https://github.com/oturra/ios-switcher/blob/master/demo/demo.html)

## Instalation

##### Standalone:

```html
<!-- Don't forget to add bootstrap -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
<link rel="stylesheet" href="dist/css/switcher.css" />
```

##### Bower:

```shell
$ bower install ios-switcher
```

---

## Usage

```html
<div class="form-switcher">
	<input type="checkbox" name="switcher-name" id="switcher-id">
	<label class="switcher" for="switcher-id"></label>
</div>
```

## Different sizes

```html

<!-- Large size -->
<div class="form-switcher form-switcher-lg">
	<input type="checkbox" name="switcher-lg-example" id="switcher-lg-example">
	<label class="switcher" for="switcher-lg-example"></label>
</div>

<!-- Normal size -->
<div class="form-switcher">
	<input type="checkbox" name="switcher-default-example" id="switcher-default-example">
	<label class="switcher" for="switcher-default-example"></label>
</div>

<!-- Small size -->
<div class="form-switcher form-switcher-sm">
	<input type="checkbox" name="switcher-sm-example" id="switcher-sm-example">
	<label class="switcher" for="switcher-sm-example"></label>
</div>
```

#### Viewport sizes

Phone sizes

```html
<!-- Large size in phones -->
<div class="form-switcher form-switcher-lg-phone">
	<input type="checkbox" name="switcher-lg-phone-example" id="switcher-lg-phone-example">
	<label class="switcher" for="switcher-lg-phone-example"></label>
</div>

<!-- Default size in phones -->
<div class="form-switcher form-switcher-md-phone">
	<input type="checkbox" name="switcher-md-phone-example" id="switcher-md-phone-example">
	<label class="switcher" for="switcher-md-phone-example"></label>
</div>

<!-- Small size in phones -->
<div class="form-switcher form-switcher-sm-phone">
	<input type="checkbox" name="switcher-sm-phone-example" id="switcher-sm-phone-example">
	<label class="switcher" for="switcher-sm-phone-example"></label>
</div>
```

Tablet sizes

```html
<!-- Large size in tablets -->
<div class="form-switcher form-switcher-lg-tablet">
	<input type="checkbox" name="switcher-lg-tablet-example" id="switcher-lg-tablet-example">
	<label class="switcher" for="switcher-lg-tablet-example"></label>
</div>

<!-- Default size in tablets -->
<div class="form-switcher form-switcher-md-tablet">
	<input type="checkbox" name="switcher-md-tablet-example" id="switcher-md-tablet-example">
	<label class="switcher" for="switcher-md-tablet-example"></label>
</div>

<!-- Small size in tablets -->
<div class="form-switcher form-switcher-sm-tablet">
	<input type="checkbox" name="switcher-sm-tablet-example" id="switcher-sm-tablet-example">
	<label class="switcher" for="switcher-sm-tablet-example"></label>
</div>
```


# Licence

The MIT License (MIT)

Copyright (c) 2016 oturra

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
