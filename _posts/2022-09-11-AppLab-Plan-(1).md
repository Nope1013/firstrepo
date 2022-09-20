---
layout: post
---
Plan for AppLab

Goals:

  - > A quiz that begins with something fun and then transitions into computer science

  - > Displaying a score at the end

  - > Learning more about code functions, connecting this to terms learned in class

What I learned:

  - > When text is turned into blocks, it becomes much easier to see what is the code is doing

  - > “console.log\[message\]” allows the computer to log key functions in a sequence

  - > Coding can get very very repetitive when you cannot use loop functions, had to do a lot of copy-pasting

  - > How to use variable functions

Things I wish I could do:

  - > Found an “if/else” block which would have been very effective for wrong/right answers but it was not compatible with the UI controls

Things I am proud of:

  - > The background music

  - > Recognizing data abstraction

  - > Balancing fun and productivity (both fun and class-oriented questions)

  - > Adding a scoring function after much trial and error

Mortagascar Code:

var score = 0;

setScreen("welcometomortagascar");

playSound("https://ia802701.us.archive.org/24/items/MadagascarILikeToMoveIt/LetsMovingOsa\_64kb.mp3", true);

onEvent("arrow", "click", function( ) {

console.log("Arrow Clicked");

setScreen("moveit\!");

});

onEvent("moveitbutton", "click", function( ) {

console.log("Start Button Clicked");

setScreen("question1");

});

onEvent("king", "click", function( ) {

console.log("King Julien Clicked");

score = score + 1;

setScreen("celebrationtime");

onEvent("celebrationtime", "click", function( ) {

setScreen("question2");

});

});

onEvent("alex", "click", function( ) {

setScreen("wompwomp");

onEvent("goback", "click", function( ) {

setScreen("question2");

});

});

onEvent("maurice", "click", function( ) {

setScreen("wompwomp");

onEvent("goback", "click", function( ) {

setScreen("question2");

});

});

onEvent("kowalski", "click", function( ) {

setScreen("wompwomp");

onEvent("goback", "click", function( ) {

setScreen("question2");

});

});

onEvent("shark", "click", function( ) {

console.log("shark Clicked");

score = score + 1;

setScreen("celebrationtime");

onEvent("celebrationtime", "click", function( ) {

setScreen("question3");

stopSound("https://ia802701.us.archive.org/24/items/MadagascarILikeToMoveIt/LetsMovingOsa\_64kb.mp3");

playSound("Windows-XP.mp3", true);

});

});

onEvent("cat", "click", function( ) {

setScreen("wompwomp");

onEvent("goback", "click", function( ) {

setScreen("question3");

playSound("Windows-XP.mp3", true);

stopSound("https://ia802701.us.archive.org/24/items/MadagascarILikeToMoveIt/LetsMovingOsa\_64kb.mp3");

});

});

onEvent("snake", "click", function( ) {

setScreen("wompwomp");

onEvent("goback", "click", function( ) {

setScreen("question3");

playSound("Windows-XP.mp3", true);

stopSound("https://ia802701.us.archive.org/24/items/MadagascarILikeToMoveIt/LetsMovingOsa\_64kb.mp3");

});

});

onEvent("mouse", "click", function( ) {

setScreen("wompwomp");

onEvent("goback", "click", function( ) {

setScreen("question3");

playSound("Windows-XP.mp3", true);

stopSound("https://ia802701.us.archive.org/24/items/MadagascarILikeToMoveIt/LetsMovingOsa\_64kb.mp3");

});

});

onEvent("morton", "click", function( ) {

console.log("Run Clicked");

setScreen("q3fr");

stopSound("Windows-XP.mp3");

});

onEvent("da", "click", function( ) {

console.log("Data Abstraction Clicked");

score = score + 1;

setScreen("correct");

onEvent("correct", "click", function( ) {

setScreen("q4");

});

});

onEvent("id", "click", function( ) {

setScreen("error");

onEvent("error", "click", function( ) {

setScreen("q4");

});

});

onEvent("aa", "click", function( ) {

setScreen("error");

onEvent("error", "click", function( ) {

setScreen("q4");

});

});

onEvent("button3", "click", function( ) {

setScreen("error");

onEvent("error", "click", function( ) {

setScreen("q4");

});

});

onEvent("si", "click", function( ) {

console.log("Yes clicked");

setScreen("error");

onEvent("error", "click", function( ) {

setScreen("q5");

});

});

onEvent("no", "click", function( ) {

console.log("No clicked");

score = score + 1;

setScreen("correct");

onEvent("correct", "click", function( ) {

setScreen("q5");

});

});

onEvent("khan", "click", function( ) {

console.log("Khan Academy Clicked");

score = score + 1;

setScreen("mortibrate");

playSound("sound://category\_achievements/melodic\_win\_10.mp3", true);

onEvent("res", "click", function( ) {

setText("yayyyy", ("Your score is" + score) + "/5");

});

});

onEvent("Dropping", "click", function( ) {

setScreen("error");

onEvent("error", "click", function( ) {

setScreen("mortibrate");

playSound("sound://category\_achievements/melodic\_win\_10.mp3", true);

onEvent("res", "click", function( ) {

setText("yayyyy", ("Your score is" + score) + "/5");

});

});

});

onEvent("notes", "click", function( ) {

setScreen("error");

onEvent("error", "click", function( ) {

setScreen("mortibrate");

playSound("sound://category\_achievements/melodic\_win\_10.mp3", true);

onEvent("res", "click", function( ) {

setText("yayyyy", ("Your score is" + score) + "/5");

});

});

});

onEvent("pracq", "click", function( ) {

setScreen("error");

onEvent("error", "click", function( ) {

setScreen("mortibrate");

playSound("sound://category\_achievements/melodic\_win\_10.mp3", true);

onEvent("res", "click", function( ) {

setText("yayyyy", ("Your score is" + score) + "/5");

});

});

});
