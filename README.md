# Devices.css

Devices.css - Modern devices in pure CSS

All devices are elegantly developed in pure CSS. The first are newly announced iPhone X and iPhone 8. More devices are coming. You can use these minimal devices in landing and screenshot showcase pages.

## Devices

- [iPhone X](https://picturepan2.github.io/devices.css/#iphone-x) (Silver)
- [iPhone 8](https://picturepan2.github.io/devices.css/#iphone-8) (Silver, Gold and Space Gray)
- [Samsung Galaxy S8](https://picturepan2.github.io/devices.css/#galaxy-s8) ( Midnight Black and Coral Blue)
- [iPad Pro](https://picturepan2.github.io/devices.css/#ipad-pro) (Silver, Gold, Rose Gold and Space Gray)
- [MacBook Pro](https://picturepan2.github.io/devices.css/#macbook) (Silver, Gold, Rose Gold and Space Gray)
- [MacBook Pro](https://picturepan2.github.io/devices.css/#macbook-pro) (Silver and Space Gray)
- [Surface Studio](https://picturepan2.github.io/devices.css/#surface-studio)
- [iMac Pro](https://picturepan2.github.io/devices.css/#imac-pro)

## What's next

- Add more devices and form factors

## Getting started

Download the compiled and minified [Devices.css files](https://github.com/picturepan2/devices.css). Include `devices.css` located in `/dist` in your website or Web app &lt;head&gt; part.

`<link rel="stylesheet" href="dist/devices.css">`

Go to [Demo page](https://picturepan2.github.io/devices.css/) to copy the device HTML source code and paste it to anywhere you want. All devices use the same HTML structure with different `device-xxx` classes.

```
<div class="device device-iphone-x">
  <div class="device-frame">
    <div class="device-content"></div>
  </div>
  <div class="device-stripe"></div>
  <div class="device-header">
    <div class="device-sensors"></div>
  </div>
  <div class="device-btns"></div>
  <div class="device-power"></div>
</div>
```

You can add any content or screenshots to the `device-content` div. The resolution aspect ratios are based on real ones.

## Custom

You can custom Devices.css by modifing SASS `.scss` files located in `src` folder.

## Browser support
Devices.css uses [Autoprefixer](https://github.com/postcss/autoprefixer) to make most styles compatible with earlier browsers. For best compatibility, these browsers are recommended:

- Chrome (LAST 4)
- Microsoft Edge (LAST 4)
- Firefox (EXTENDED SUPPORT RELEASE)
- Safari (LAST 4)
- Opera (LAST 4)

Built with ♥ by [Yan Zhu](https://twitter.com/picturepan2). Feel free to submit a pull request. Help is always appreciated.

Devices.css is completely free to use. If you enjoy it, please consider [donating via Paypal](https://www.paypal.me/picturepan2) for the further development. ♥ 
