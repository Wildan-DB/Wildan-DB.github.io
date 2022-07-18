function init() {
Tabletop.init( { key: ‘https://docs.google.com/spreadsheets/d/1j-Ymd_GCQNjRKsPjs7FRCxkHcFj30YUwL5ko1tdsQl0/pubhtml',
callback: function(data, tabletop) {
console.log(data)
},
simpleSheet: true } )
}
window.addEventListener(‘DOMContentLoaded’, init)
