# null-style
* {
  padding: 0;
  margin: 0;
  border: 0;
}

*, *:before, *:after {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}

:focus, :active {
  outline: none;
}

a:focus, a:active {
  outline: none;
}

nav, footer, header, aside {
  display: block;
}

html, body {
  height: 100%;
  width: 100%;
  margin: 0;
  padding: 0;
  min-width: 320px;
  position: relative;
  color: #000;
}

body {
  font-size: 100%;
  line-height: 1;
  font-size: 14px;
  font-family: "PT Sans";
  -ms-text-size-abjust: 100%;
  -moz-text-size-abjust: 100%;
  -webkit-text-size-abjust: 100%;
}
body.lock {
  overflow: hidden;
}
@media (max-width: 767.98px) {
  body.lock {
    width: 100%;
    position: fixed;
    overflow: hidden;
  }
}

imput, button, textarea {
  font-family: inherit;
}

input::-ms-clear {
  display: none;
}

button {
  cursor: pointer;
}

button::-moz-focus-inner {
  padding: 0;
  border: 0;
}

a, a:visited {
  text-decoration: none;
}

a:hover {
  text-decoration: none;
}

ul li {
  list-style: none;
}

img {
  vertical-align: top;
}

h1, h2, h3, h4, h5, h6 {
  font-size: inherit;
  font-weight: 400;
}

.wrapper {
  width: 100%;
  min-height: 100%;
  overflow: hidden;
}
.container {
  max-width: 820px;
  margin: 0 auto;
  width: 100%;
}
@media (max-width: 750px) {
  .container {
    max-width: 750px;
  }
}
@media (max-width: 767.98px) {
  .container {
    max-width: none;
    padding: 0 10px;
  }
}
