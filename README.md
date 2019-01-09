# Slack-Solarized-Dark

A simple clean solarized dark theme for slack

*navigate to ->*
1. Windows: %homepath%\AppData\Local\slack\
2. Mac: /Applications/Slack.app/Contents/
3. Linux: /usr/lib/slack/

>***add this to the end of your ssb-interop.js file ->***
>
>```// dark solarized
>document.addEventListener('DOMContentLoaded', function () {
>  $.ajax({
>      url: 'https://raw.githubusercontent.com/kyle-barth/Slack-Solarized-Dark/master/solarized.css',
>      success: function (css) {
>          $("<style></style>").appendTo('head').html(css);
>      }
>  });
>```

Code by GitHub user: earlduque
(I just chamged some values for to achievce a dark solarized appearance)
