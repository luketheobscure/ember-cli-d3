# ember-cli-d3

[![Build Status](https://travis-ci.org/lightblade/ember-cli-d3.svg?branch=master)](https://travis-ci.org/lightblade/ember-cli-d3)
[![npm version](https://badge.fury.io/js/ember-cli-d3.svg)](http://badge.fury.io/js/ember-cli-d3)
[![Code Climate](https://codeclimate.com/github/lightblade/ember-cli-d3/badges/gpa.svg)](https://codeclimate.com/github/lightblade/ember-cli-d3)
[![Dependency Status](https://david-dm.org/lightblade/ember-cli-d3.svg)](https://david-dm.org/lightblade/ember-cli-d3)
[![devDependency Status](https://david-dm.org/lightblade/ember-cli-d3/dev-status.svg)](https://david-dm.org/lightblade/ember-cli-d3#info=devDependencies)

`ember-cli-d3` is an [ember-cli](http://www.ember-cli.com/) addon to provide a framework
to integrate [d3](http://d3js.org) visualizations into Ember applications.

See [github pages](http://lightblade.github.io/ember-cli-d3/) for demo.

Please note that this project is still in pre-alpha stage and I'm seeking feedback on how it
can be improved.

## Composability

`ember-cli-d3` tries to follow the composability pattern of d3 as much as possible while
fully utilizing the advantage of having HTMLBars templates. The result is that it allows
you to integrate many of the d3 plugins that exists out there.

## Bundled Visuals

Currently, these visuals are bundled with the addon. However, it is not the goal of this project to become a widget library. It is possible that these visuals will be removed from the addon and exist only as part of demo in the dummy app. They will not be officially supported, but you are welcome to copy the source code from the dummy app to your own application.

* [ ] Cartesian
  * [ ] Bar Chart
    * [x] Grouped Bars
    * [x] Stacked Bars
    * [ ] Waterfall
  * [x] Line Chart
    * [ ] Area Chart
    * [ ] Stacked Area

# Usage

## Installation

* `git clone` this repository
* `npm install`
* `bower install`

## Running

* `ember server`
* Visit your app at http://localhost:4200.

## Running Tests

* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://www.ember-cli.com/](http://www.ember-cli.com/).

## License

MIT