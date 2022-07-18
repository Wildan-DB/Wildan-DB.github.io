```js
function init() {
          Papa.parse('https://docs.google.com/spreadsheets/d/1j-Ymd_GCQNjRKsPjs7FRCxkHcFj30YUwL5ko1tdsQl0/pubhtml', {
          download: true,
          header: true,
          complete: function(results) {
            var data = results.data
            console.log(data)
          }
        })
window.addEventListener('DOMContentLoaded', init)
```
