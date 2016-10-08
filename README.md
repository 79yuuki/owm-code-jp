# owm-code-jp

This module translate the OpenWeatherMap code in Japanese.

[OpenWeatherMap のコード一覧](http://openweathermap.org/weather-conditions) の Code で返ってくる英語の情報を日本語で返すモジュールです。

## 使い方

```js
var owm-code-jp = require('owm-code-jp');

var weather = owm-code-jp(801);

console.log(weather.main); // 曇り
console.log(weather.description); // ほとんど雲がない

```

個人用に作ったので荒いですが、日本語が間違ってたり使いやすい様に変えたいとき、プルリクエスト歓迎です。
