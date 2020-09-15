JavaScript is written in plain text, just like HTML and CSS, so you do not
need any new tools to write a script. This example adds a greeting into an
HTML page. The greeting changes depending on the time of day.


### Example Variable Code

var today= new Date();
var hourNow = today.getHours();
var greeting;
if (hourNow > 18) {
greeting= 'Good evening!';
else if (hourNow > 12) {
greeting = ' Good afternoon!';
else if (hourNow > 0) {
greeting = 'Good morni ng!';
else {
greeting = 'Welcome! ' ;
document .write( ' <h3>' +greeting + ' </ h3>');

- Save
this file with the name
add-content.html


You may see JavaScript in the HTML between
opening <script> and closing </script> tags
(but it is better to put scripts in their own files).

