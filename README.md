# Slack-Solarized-Dark

A simple clean solarized dark theme for slack

*navigate to ->*
1. Windows: %homepath%\AppData\Local\slack\
2. Mac: /Applications/Slack.app/Contents/
3. Linux: /usr/lib/slack/

*navigate into the most recent version of slack e.g `\app-3.4.2`*

Then continue to navigate to ->
\resources\app.asar.unpacked\src\static

example full path -> %homepath%\AppData\Local\slack\app-3.4.2\resources\app.asar.unpacked\src\static

>***add this to the end of your ssb-interop.js file ->***
>
>```// solarized theme
>document.addEventListener('DOMContentLoaded', function () {
>  $.ajax({
>      url: 'https://raw.githubusercontent.com/kyle-barth/Slack-Solarized-Dark/master/solarized.css',
>      success: function (css) {
>          $("<style></style>").appendTo('head').html(css);
>      }
>  });
>});

Code by GitHub user: [earlduque](https://github.com/earlduque)
(I just changed some values for to achievce a dark solarized appearance)
