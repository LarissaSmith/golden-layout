# [Golden Layout](https://golden-layout.com/)  [![NPM version](https://badge.fury.io/js/golden-layout.svg)](http://badge.fury.io/js/golden-layout) [![Build Status](https://travis-ci.org/deepstreamIO/golden-layout.svg?branch=master)](https://travis-ci.org/deepstreamIO/golden-layout)

![Screenshot](https://cloud.githubusercontent.com/assets/512416/4584449/e6c154a0-4ffa-11e4-81a8-a7e5f8689dc5.PNG)

# [https://golden-layout.com/](https://golden-layout.com/)

## Installation

Add `golden-layout` to your bower.json, or [download](https://golden-layout.com/download/) the source.

## Features

Note: this branch has been modified from the base branch with the following features
disableStacking on individual items (Hopefully to be accepted soon)
Use flexbox instead of pixel sizes to cut down on javascript (Hopefully to be accepted eventually)
Adds feature to reverse a row or column in the config.

Not all of golden layout's features have been fully tested with flexbox.
Features for docking and maximizing panels could use more testing
Removing the event listener on window resize means that the _respectMinWidth doesn't run
on resize. That should be addressed before flexbox can be accepted to the base branch.
It would be nice to respect min height in that function as well.
It was necessary to add absolute positioning to a div to make it work in IOS Safari

* Native popup windows
* Completely themeable
* Comprehensive API
* Powerful persistence
* Works in IE8+, Firefox, Chrome
* Reponsive design


## [Examples](https://golden-layout.com/examples/)

## License
MIT
