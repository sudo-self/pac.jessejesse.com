# pac.jessejesse.com
<img width="666" alt="Screenshot 2023-06-24 at 10 50 12 PM" src="https://github.com/sudo-self/pac.jessejesse.com/assets/119916323/7e968ad1-ee09-4726-b6c4-cb9348b7d917">

### <html> <head>
<meta charset="utf-8" /> <title>JRs Pacman</title>
‹style type="text/css">
@font-face {
font-family: 'BDCartoonShoutRegular';
src: url('BD_Cartoon_Shout-webfont.ttf') format('truetype');
font-weight: normal; font-style: normal;
}
#pacman {
height: 450px; width:342px;
margin:20px auto;
}
#shim {
font-family: BDCartoonShoutRegular; position:absolute;
visibility:hidden
}
h1 { font-family: BDCartoonShoutRegular; text-align:center; } body { width:342px; margin:Opx auto; font-family:sans-serif; } a { text-decoration: none; }
</style>
</head>
<body>
‹div id="shim">shim for font face</div>
<h1>Jesse's Pacman</h1>
source code on <a href="https://github.com/sudo-self">Github</a>
<div id="pacman"></div> <script src="pacman.js"»</script> «script src="modernizr-1.5.min.js"></script>
<script>
var el = document.getElementById("pacman");
if (Modernizr.canvas && Modernizr. localstorage &&
Modernizr.audio & (Modernizr.audio.ogg || Modernizr.audio.mp3) ) {
window.setTimeout (function () { PACMAN.init(el, "./"); }, 0);
† else {
el.innerHTML = "Sorry, needs a decent browser<br /><small>" +
"(firefox 3.6+, Chrome 4+, Opera 10+ and Safari 4+)</small>";
}
</script>
