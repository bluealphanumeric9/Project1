# Project1 - Magic 8-ball 

//This is the code in JavaScript:

let userName='';
userName ? console.log(`Hello! ${userName}`) : console.log('Hello!');

const userQuestion ='Confirm.'
console.log(`The user asked: ${userQuestion}?`);
const randomNumber = Math.floor(Math.random()*8); 

let eightBall='';

if (randomNumber === 0){
  eightBall='It is certain'
}
else if  (randomNumber === 1){
eightBall='It is decidedly so'
}
else if  (randomNumber === 2){
eightBall='Reply hazy try again'
}
else if  (randomNumber === 3){
eightBall='Cannot predict now'
}
else if  (randomNumber === 4){
eightBall='Do not count on it'
}
else if  (randomNumber === 5){
eightBall='My sources say no'
}
else if (randomNumber === 6){
eightBall='Outlook not so good'
}
else {
eightBall='Signs point to yes'
};

console.log(`The answer is ${eightBall}`);



//Comments:

/*1. Why are some variables constant and other change the value?

    This is due to the nature of the problem or the variable itself. Random number produced is a constant which changes between 0 and 7 in every execution of the algorithm. What is the next step? After one random number is chosen, the empty string "eightBall" is renamed and the printed to the console. 


2. It is a simple usage of if-else if - else logic and surely, apart from how to understand which variable type exactly to use (constant or changeable) and hence which syntax to employ( "let ... = '...' " or "constant = ....") simple list of different cases. 
3. This example is important since it can be seen as the basis for much more complex structre flows and system architectures, since most of them will follow the same "logic", only the complexity of the task and modelling thereof will differ. */

