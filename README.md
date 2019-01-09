# Slack-Solarized-Dark

A simple clean solarized dark theme for slack

navigate to:


>***add this to the end of your ssb-interop.js file ->***
>
>```// dark solarized
>document.addEventListener('DOMContentLoaded', function () {
>  $.ajax({
>      url: 'https://raw.githubusercontent.com/kyle-barth/Slack-Solarized-Dark/solarized.css',
>      success: function (css) {
>          $("<style></style>").appendTo('head').html(css);
>      }
>  });```
>