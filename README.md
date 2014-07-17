inspect-reset
=============

~~~~~~~~~~~~~~~~~~~~

/* --------------------------------------------------------
INSPECT RESET - CSS
@author name Daniel Beff
@author email daniel.beff@gmail.com
@author site http://www.danielbeff.com
@version 1.0.0
@licence MIT
-------------------------------------------------------- */
html {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    /*Prevent mobile/tablet text size adjust after orientation change, without disabling user zoom.*/
    -webkit-text-size-adjust: 100%;
    -ms-text-size-adjust: 100%;
    text-size-adjust: 100%;
}
body{
    padding: 0;
    margin: 0;
}
/* --------------------------------------------------------
// TYPOGRAPHY
-------------------------------------------------------- */
a {
    cursor: pointer;
    text-decoration: none;
    display: inline-block;
}
/* --------------------------------------------------------
// LISTS
-------------------------------------------------------- */
nav ul {
    list-style: none;
}
/* --------------------------------------------------------
// FORM
-------------------------------------------------------- */
input, textarea, select {
    display: block;
    -webkit-font-smoothing: antialiased;
}
input:focus, textarea:focus, select:focus {
    outline: none;
}
input[disabled], textarea[disabled], select[disabled] {
    cursor: not-allowed;
}
/* --------------------------------------------------------
// TABLE
-------------------------------------------------------- */
table {
    border-collapse: collapse;
}
tr, td {
    vertical-align: middle;
}
/* --------------------------------------------------------
// EMBEDDED
-------------------------------------------------------- */
img {
  border: 0;
}
/* Correct overflow not hidden in IE 9/10/11 */
svg:not(:root) {
  overflow: hidden;
}

~~~~~~~~~~~~~~~~~~~~
