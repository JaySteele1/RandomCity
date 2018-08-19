# RandomCity 
// Here i put the variables outside the function making them global, just for practice. I could've put all
// the variables in the function which would make them local to this shitTalk() function only.
var randomCities = ["Chicago", "Toledo", "Denver", "Westminster", "Detroit"];
var randomAdjectives = ["pretty", "a dump", "crowded", "quiet", "crime loaded"];
var randomCity = randomCities[Math.floor(Math.random() * 5)]; // Can use the .length also see below
var randomAdjective = randomAdjectives[Math.floor(Math.random() * randomAdjectives.length)]; // Can use the *5 also see above

function shitTalk() {
    document.write(randomCity + " is " + randomAdjective + " dont you think?");
};
shitTalk();


// Here is the same code just not as a function, again just for practice. Both have the same random results.
/*
var randomCities = ["Chicago", "Toledo", "Denver", "Westminster", "Detroit"];
var randomAdjectives = ["pretty", "a dump", "crowded", "quiet", "crime loaded"];
var randomCity = randomCities[Math.floor(Math.random() * 5)];
var randomAdjective = randomAdjectives[Math.floor(Math.random() * randomAdjectives.length)];
var randomShitTalk = (randomCity + " is " + randomAdjective + " dont you think?");
document.write(randomShitTalk);
*/


