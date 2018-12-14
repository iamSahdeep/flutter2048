# Flutter2048

 I have just started learning Flutter. It is an Example of loading local html files (2048 game) with Flutter webView. Only 25 lines of code :)
 
### Download App
<a href='https://play.google.com/store/apps/details?id=com.sahdeepsingh.flutter2048&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' width="200" height="100"/></a>

## Plugins Used
  - <a href="https://github.com/fluttercommunity/flutter_webview_plugin"> flutter_webview_plugin </a> for webView
  - <a href="https://github.com/fluttercommunity/flutter_launcher_icons"> flutter_launcher_icons </a> for icon regeneration
  - Link to the original game https://github.com/uberspot/2048/tree/7986ea0432fc9fd6634dfeaff3b966ecb7aa78de

## Screenshots

<img src="assets/1.jpeg" width="200" height="340"> - <img src="assets/2.jpeg" width="200" height="340">

<img src="assets/3.jpeg" width="200" height="340"> - <img src="assets/4.jpeg" width="200" height="340">


### How to use flutter_webview_plugin for local files?
 - Add your files in the ```android/app/src/main/assets``` 
 - use the url like this 
    ```  
    return WebviewScaffold(
      url: 'file:///android_asset/index.html',
      allowFileURLs: true,
      withZoom: false,
    );
    ```
 - check this issue for more info https://github.com/fluttercommunity/flutter_webview_plugin/issues/23


### Licence
```
MIT License

Copyright (c) 2018 Sahdeep Singh

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
```

## Getting Started

For help getting started with Flutter, view our online
[documentation](https://flutter.io/).


