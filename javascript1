// For Node.js environment using readline
const readline = require('readline');
const rl = readline.createInterface({
    input: process.stdin,
    output: process.stdout
});

rl.question("Enter a sentence: ", function(inputSentence) {
    var reversedSentence = reverseWords(inputSentence);
    console.log("Original sentence: " + inputSentence);
    console.log("Reversed sentence: " + reversedSentence);
    rl.close();
});

function reverseWords(sentence) {
    var words = sentence.split(' ');

    var reversedWords = words.map(function(word) {
        return word.split('').reverse().join('');
    });

    var reversedSentence = reversedWords.join(' ');

    return reversedSentence;
}
