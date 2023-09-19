# Bookmarklet Ver

## Steps:
1. right click your bookmarks bar and click add page
2. set the name to 'poki fullscreener'
3. set the url/adress to:

javascript:var elem = document.getElementById("game-element"); function openFullscreen() {if (elem.requestFullscreen) {elem.requestFullscreen();} else if (elem.webkitRequestFullscreen) {elem.webkitRequestFullscreen();} else if (elem.msRequestFullscreen) {elem.msRequestFullscreen();}}; openFullscreen();
