[![Build status](https://badge.buildkite.com/08d877adb02db96a893c76bab52a6667a7173ca5a3a01bd841.svg)](https://buildkite.com/neto-ecommerce/take-me-home-theme)

# Take Me Home Theme

Take Me Home is one of Neto's free themes!

![](https://design.neto.com.au/assets/themerepos5/takemehome.jpg)

## Installation

**Theme editor**

The safest way to install Take Me Home is through Neto's theme store. Go to **Webstore** > **Theme editor** in your Neto control panel, hover over _Take Me Home_ and click the green _Install_ button.

**Directly install**

To install the latest version of Take Me Home directly from this repository you simply need to upload the `src` directory from this repository into the `httpdocs/assets/themes` directory on your Neto website. You should also rename this new `src` directory to whatever you would like your custom theme to be named.

For the above, you will need FTP access to your Neto website, which you can request [here](http://forms.neto.com.au/design/requestftp.html).

## Documentation

Documentation for designers and developers can be found [here](https://developers.neto.com.au/).

As Take Me Home is built almost entirely upon Bootstrap 4, the [Bootstrap documentation](https://getbootstrap.com/docs/4.1/getting-started/introduction/) is perhaps the most valuable source of documentation for a web designer who isn't looking to build complex functionality.

## Compiling .scss files

If you are not comfortable working with [SASS](https://sass-lang.com/), you are best off writing all CSS in your own custom CSS file. As our `.scss` files are compiled into `app.css`, avoid modifying `app.css`. Otherwise, if for whatever reason you eventually do need to re-compile the `.scss` files, any changes to `app.css` would be lost.

If you are comfortable with SASS, you're best off developing in you're own `.scss` file and adding it to the imports in `src/scss/app.scss`, which needs to be compiled to `src/css/app.css` using Gulp.

If you are compiling `.scss` files for the purpose of contributing to Take Me Home, follow these steps:

_Note that steps 1 and 2 only need to be completed once per system, so no need to repeat them again._

1. Install [node.js](https://nodejs.org/),
2. CD into your local folder of Take Me Home and run the `npm i` command to install all relevant dependencies,
3. Run either of these two commands:
    - `npm run build` — this will compile your `.scss` files.
    - `npm run watch` — this will watch your `.scss` files and compile them as they change.

## Testing

We have a simple testing guide located [here](/testing.md).

## Support

The current version of Take Me Home will only work on websites running Neto 6+. For older websites, you will need to install from a previous release.

## Creators

Made w/ 🔥 by [Neto E-commerce Solutions](http://neto.com.au).
