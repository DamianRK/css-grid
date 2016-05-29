CSS responsive grid system with Flexbox
==================================

## Description

Grid system has 12 columns. No matter the size of the browser, each of these columns will always have an equal width.

## Requirements

Working perfectly with: https://github.com/DamianRK/magento-gulp-sass
Requires:
* bp() mixin
* $bp-xsmall, $bp-small, $bp-medium, $bp-large, $bp-xlarge variables

## Example

    <div class="row">
        <div class="column s-12">This div is 12-columns wide .s-12</div>
        <div class="column xs-12 s-6 m-3">.xs-12 .s-6 .m-3</div>
        <div class="column xs-12 s-6 m-3">.xs-12 .s-6 .m-3</div>
        <div class="column s-6 m-3">.s-6 .m-3</div>
        <div class="column s-6 m-3">.s-6 .m-3</div>
    </div>


![Alt text](/test/img/grid.001.png "Grid system")


## Author

Karol Parfienczyk <parfienczyk@gmail.com>
 
