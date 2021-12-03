# SafeSize Engagement Screen Challenge

An HTML/CSS challenge from SafeSize.

Technologies used: HTML/SASS

## Structure

This project follows a much simpler version of the 7-1 SASS Architecture.

* **_base.scss** : Contains abstract scss (a few useful functions and mixins) and typography rules.
* **_components.scss** : As expected just reusable components or components that might be reused in the future.
* **_layout.scss** : Page specific styles that I could not create components out of.

## Vendors

I'm only using the [include-media](https://github.com/eduardoboucas/include-media) npm package for a more intuitive media query syntax, but I'm not using any other packages.

## Notes

* Some assets were missing from the mockup, so I had to either ignore them entirely (eg. open_fitting_list.html the box image at the center is missing), or just replace them with something I thought fitted. (MDI SVG for the shoe icon)

* In the mockup Stratos was used frequently, which is a premium Adobe font, so I used Heebo instead.

