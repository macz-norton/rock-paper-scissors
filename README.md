# rock-paper-scissors

Creating a rock paper scissors game with JavaScript

Create vars: Rock, Paper, and Scissors
var rps = ["rock", "papers", "scissors"];
Prompt: Rock, Paper, or Scissors
var userPrompt = prompt("Rock, Paper, Scissors");

Send input to lower case:
var userChoice = userPrompt.toLowerCase();

Generate random number:
Rock = 0, Paper = 1, Scissors = 2
var rps rpsRandom = rps[math.floor(math.random()*3)]
if input = rock(0), rps = rock(0) then TIE
if input = rock(0), rps = paper(1) then LOSE
if input = rock(0), rps = scissors(2) then WIN

if TIE no score change
if WIN +1 user score
if LOSE +1 computer score
