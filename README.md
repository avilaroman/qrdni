# QRDNI 

## Soft para capturar QR del DNI Argentino

## Html5-El QR funciona con librerias en HTML5 para cualquier Navegador actual del 2025

#Example: [scanapp.org](https://scanapp.org).

## Lightweight & cross-platform QR Code and Bar code scanning library for the web

Use this lightweight library to easily / quickly integrate QR code, bar code, and other common code scanning capabilities to your web application.

## Key highlights
-   🔲 scanning [different types of bar codes and QR codes](#supported-code-formats).

-   🖥 [different platforms](#supported-platforms) be it Android, IOS, MacOs, Windows or Linux

-   🌐  [different browsers](#supported-platforms) like Chrome, Firefox, Safari, Edge, Opera ...

-   📷  scanning with camera as well as local files

-   ➡️  viene con un [end to end library with UI](#easy-mode---with-end-to-end-scanner-user-interface) as well as a [low level library to build your own UI with](#pro-mode---if-you-want-to-implement-your-own-user-interface).

-   🔦 Supports customisations like [flash/torch support](#showtorchbuttonifsupported---boolean--undefined), zooming etc.


Supports two kinds of APIs

-   `Html5QrcodeScanner` — End-to-end scanner with UI, integrate with less than ten lines of code.
    
-   `Html5Qrcode` — Powerful set of APIs you can use to build your UI without worrying about camera setup, handling permissions, reading codes, etc.

> Support for scanning local files on the device is a new addition and helpful for the web browser which does not support inline web-camera access in smartphones. **Note:** This doesn't upload files to any server — everything is done locally.

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/mebjas/html5-qrcode/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/mebjas/html5-qrcode/tree/master) [![GitHub issues](https://img.shields.io/github/issues/mebjas/html5-qrcode)](https://github.com/mebjas/html5-qrcode/issues) [![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/mebjas/html5-qrcode)](https://github.com/mebjas/html5-qrcode/releases) ![GitHub](https://img.shields.io/github/license/mebjas/html5-qrcode) [![Codacy Badge](https://app.codacy.com/project/badge/Grade/51e4f0ef8b0b42e1b93ce29875dd23a0)](https://www.codacy.com/gh/mebjas/html5-qrcode/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=mebjas/html5-qrcode&amp;utm_campaign=Badge_Grade) [![Gitter](https://badges.gitter.im/html5-qrcode/community.svg)](https://gitter.im/html5-qrcode/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

![GitHub all releases](https://img.shields.io/github/downloads/mebjas/html5-qrcode/total?label=Github%20downloads&style=for-the-badge) [![npm](https://img.shields.io/npm/dw/html5-qrcode?label=npm%20downloads&style=for-the-badge)](https://www.npmjs.com/package/html5-qrcode) [![](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://bit.ly/3CZiASv)

| <img src="https://scanapp.org/assets/github_assets/pixel6pro-optimised.gif" width="180px" /> | <img src="https://scanapp.org/assets/github_assets/pixel4_barcode_480.gif" width="180px" />|
| -- | -- |
| _Demo at [scanapp.org](https://scanapp.org)_ | _Demo at [qrcode.minhazav.dev](https://qrcode.minhazav.dev) - **Scanning different types of codes**_ |

## We need your help!

![image](https://user-images.githubusercontent.com/3007365/222830114-e5bcca15-bf8a-434e-9f48-339e82a0a4ef.png)
Help incentivise feature development, bug fixing by supporting the sponsorhip goals of this project. See [list of sponsered feature requests here](https://github.com/mebjas/html5-qrcode/wiki/Feature-request-sponsorship-goals#feature-requests).

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/L3L84G0C8)

## Documentation

The documentation for this project has been moved to [scanapp.org/html5-qrcode-docs](https://scanapp.org/html5-qrcode-docs/).

-   [Getting started](https://scanapp.org/html5-qrcode-docs/docs/intro)
-   [Supported frameworks](https://scanapp.org/html5-qrcode-docs/docs/supported_frameworks)
-   [Supported 1D and 2D Code formats](https://scanapp.org/html5-qrcode-docs/docs/supported_code_formats)
-   [Detailed API documentation](https://scanapp.org/html5-qrcode-docs/docs/apis)

## Supported platforms

We are working continuously on adding support for more and more platforms. If you find a platform or a browser where the library is not working, please feel free to file an issue. Check the [demo link](https://blog.minhazav.dev/research/html5-qrcode.html) to test it out.

**Legends**
-   ![](https://scanapp.org/assets/github_assets/done.png) Means full support — inline webcam and file based 
-   ![](https://scanapp.org/assets/github_assets/partial.png) Means partial support — only file based, webcam in progress

### PC / Mac

| <img src="https://scanapp.org/assets/github_assets/browsers/firefox_48x48.png" alt="Firefox" width="24px" height="24px" /><br/>Firefox | <img src="https://scanapp.org/assets/github_assets/browsers/chrome_48x48.png" alt="Chrome" width="24px" height="24px" /><br/>Chrome | <img src="https://scanapp.org/assets/github_assets/browsers/safari_48x48.png" alt="Safari" width="24px" height="24px" /><br/>Safari | <img src="https://scanapp.org/assets/github_assets/browsers/opera_48x48.png" alt="Opera" width="24px" height="24px" /><br/>Opera | <img src="https://scanapp.org/assets/github_assets/browsers/edge_48x48.png" alt="Edge" width="24px" height="24px" /><br/> Edge
| --------- | --------- | --------- | --------- | ------- |
|![](https://scanapp.org/assets/github_assets/done.png)| ![](https://scanapp.org/assets/github_assets/done.png)| ![](https://scanapp.org/assets/github_assets/done.png)| ![](https://scanapp.org/assets/github_assets/done.png) | ![](https://scanapp.org/assets/github_assets/done.png)

### Android

| <img src="https://scanapp.org/assets/github_assets/browsers/chrome_48x48.png" alt="Chrome" width="24px" height="24px" /><br/>Chrome | <img src="https://scanapp.org/assets/github_assets/browsers/firefox_48x48.png" alt="Firefox" width="24px" height="24px" /><br/>Firefox | <img src="https://scanapp.org/assets/github_assets/browsers/edge_48x48.png" alt="Edge" width="24px" height="24px" /><br/> Edge | <img src="https://scanapp.org/assets/github_assets/browsers/opera_48x48.png" alt="Opera" width="24px" height="24px" /><br/>Opera | <img src="https://scanapp.org/assets/github_assets/browsers/opera-mini_48x48.png" alt="Opera-Mini" width="24px" height="24px" /><br/> Opera Mini | <img src="https://scanapp.org/assets/github_assets/browsers/uc_48x48.png" alt="UC" width="24px" height="24px" /> <br/> UC
| --------- | --------- | --------- | --------- |  --------- | --------- |
|![](https://scanapp.org/assets/github_assets/done.png)| ![](https://scanapp.org/assets/github_assets/done.png)| ![](https://scanapp.org/assets/github_assets/done.png)| ![](https://scanapp.org/assets/github_assets/done.png)| ![](https://scanapp.org/assets/github_assets/partial.png) | ![](https://scanapp.org/assets/github_assets/partial.png) 

### IOS

| <img src="https://scanapp.org/assets/github_assets/browsers/safari_48x48.png" alt="Safari" width="24px" height="24px" /><br/>Safari | <img src="https://scanapp.org/assets/github_assets/browsers/chrome_48x48.png" alt="Chrome" width="24px" height="24px" /><br/>Chrome | <img src="https://scanapp.org/assets/github_assets/browsers/firefox_48x48.png" alt="Firefox" width="24px" height="24px" /><br/>Firefox | <img src="https://scanapp.org/assets/github_assets/browsers/edge_48x48.png" alt="Edge" width="24px" height="24px" /><br/> Edge 
| --------- | --------- | --------- | --------- |
|![](https://scanapp.org/assets/github_assets/done.png)| ![](https://scanapp.org/assets/github_assets/done.png)* | ![](https://scanapp.org/assets/github_assets/done.png)* | ![](https://scanapp.org/assets/github_assets/partial.png) 


> \* Supported for IOS versions >= 15.1
>
> Before version 15.1, Webkit for IOS is used by Chrome, Firefox, and other browsers in IOS and they do not have webcam permissions yet. There is an ongoing issue on fixing the support for iOS - [issue/14](https://github.com/mebjas/html5-qrcode/issues/14)

### Framework support
The library can be easily used with several other frameworks, I have been adding examples for a few of them and would continue to add more.

|<img src="https://scanapp.org/assets/github_assets/html5.png" width="30px" />| <img src="https://scanapp.org/assets/github_assets/vuejs.png" width="30px" />|<img src="https://scanapp.org/assets/github_assets/electron.png" width="30px" /> | <img src="https://scanapp.org/assets/github_assets/react.svg" width="30px" /> | <img src="https://seeklogo.com/images/L/lit-logo-6B43868CDC-seeklogo.com.png" width="30px" />
| -------- | -------- | -------- | -------- | -------- |
| [Html5](./examples/html5) | [VueJs](./examples/vuejs) | [ElectronJs](./examples/electron) | [React](https://github.com/scanapp-org/html5-qrcode-react) | [Lit](./examples/lit)

### Supported Code formats
Code scanning is dependent on [Zxing-js](https://github.com/zxing-js/library) library. We will be working on top of it to add support for more types of code scanning. If you feel a certain type of code would be helpful to have, please file a feature request.

| Code | Example |
| ---- | ----- |
| QR Code | <img src="https://scanapp.org/assets/github_assets/qr-code.png" width="200px" /> |
| AZTEC | <img src="https://scanapp.org/assets/github_assets/aztec.png" /> |
| CODE_39|  <img src="https://scanapp.org/assets/github_assets/code_39.gif" /> |
| CODE_93| <img src="https://scanapp.org/assets/github_assets/code_93.gif" />|
| CODE_128| <img src="https://scanapp.org/assets/github_assets/code_128.gif" />|
| ITF| <img src="https://scanapp.org/assets/github_assets/itf.png" />|
| EAN_13|<img src="https://scanapp.org/assets/github_assets/ean13.jpeg" /> |
| EAN_8| <img src="https://scanapp.org/assets/github_assets/ean8.jpeg" />|
| PDF_417| <img src="https://scanapp.org/assets/github_assets/pdf417.png" />|
| UPC_A| <img src="https://scanapp.org/assets/github_assets/upca.jpeg" />|
| UPC_E| <img src="https://scanapp.org/assets/github_assets/upce.jpeg" />|
| DATA_MATRIX|<img src="https://scanapp.org/assets/github_assets/datamatrix.png" /> |
| MAXICODE*| <img src="https://scanapp.org/assets/github_assets/maxicode.gif" /> |
| RSS_14*| <img src="https://scanapp.org/assets/github_assets/rss14.gif" />|
| RSS_EXPANDED*|<img src="https://scanapp.org/assets/github_assets/rssexpanded.gif" /> |

> *Formats are not supported by our experimental integration with native
> BarcodeDetector API integration ([Read more](/experimental.md)).

## Description - [View Demo](https://blog.minhazav.dev/research/html5-qrcode.html)

> See an end to end scanner experience at [scanapp.org](https://scanapp.org).

This is a cross-platform JavaScript library to integrate QR code, bar codes & a few other types of code scanning capabilities to your applications running on HTML5 compatible browser.

Supports:
-   Querying camera on the device (with user permissions)
-   Rendering live camera feed, with easy to use user interface for scanning
-   Supports scanning a different kind of QR codes, bar codes and other formats
-   Supports selecting image files from the device for scanning codes

## How to use

Find detailed guidelines on how to use this library on [scanapp.org/html5-qrcode-docs](https://scanapp.org/html5-qrcode-docs/docs/intro).

## Demo
<img src="https://scanapp.org/assets/github_assets/qr-code.png" width="200px"><br />
_Scan this image or visit [blog.minhazav.dev/research/html5-qrcode.html](https://blog.minhazav.dev/research/html5-qrcode.html)_

### For more information
Check these articles on how to use this library:
<!-- TODO(mebjas) Mirgate this link to blog.minhazav.dev -->
-   [QR and barcode scanner using HTML and JavaScript](https://minhazav.medium.com/qr-and-barcode-scanner-using-html-and-javascript-2cdc937f793d)
-   [HTML5 QR Code scanning — launched v1.0.1 without jQuery dependency and refactored Promise based APIs](https://blog.minhazav.dev/HTML5-QR-Code-scanning-launched-v1.0.1/).
-   [HTML5 QR Code scanning with JavaScript — Support for scanning the local file and using default camera added (v1.0.5)](https://blog.minhazav.dev/HTML5-QR-Code-scanning-support-for-local-file-and-default-camera/)

## Screenshots
![screenshot](https://scanapp.org/assets/github_assets/screen.gif)<br />
_Figure: Screenshot from Google Chrome running on MacBook Pro_

