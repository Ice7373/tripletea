# tripletea
function getRandomNumber(min, max) {
    return Math.floor(Math.random() * (max - min)) + min;
}

// Example usage:
const randomNum = getRandomNumber(1, 10); // Random number between 1 and 9
console.log(randomNum);
function getRandomNumber(min, max) {
    return Math.floor(Math.random() * (max - min)) + min;
}

// Example usage:
const randomNum = getRandomNumber(1, 10); // Random number between 1 and 9
console.log(randomNum);
function getRandomItem(arr) {
    const randomIndex = Math.floor(Math.random() * arr.length);
    return arr[randomIndex];
}

// Example usage:
const fruits = ['apple', 'banana', 'orange', 'mango'];
const randomFruit = getRandomItem(fruits);
console.log(randomFruit);
function getRandomString(length) {
    const characters = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789';
    let result = '';
    const charactersLength = characters.length;
    for (let i = 0; i < length; i++) {
        result += characters.charAt(Math.floor(Math.random() * charactersLength));
    }
    return result;
}

// Example usage:
const randomStr = getRandomString(10); // Random string of length 10
console.log(randomStr);
function getRandomHexColor() {
    const hex = Math.floor(Math.random() * 0xffffff).toString(16);
    return `#${hex.padStart(6, '0')}`;
}

// Example usage:
const randomColor = getRandomHexColor();
console.log(randomColor);
function getRandomBoolean() {
    return Math.random() >= 0.5;
}

// Example usage:
const randomBool = getRandomBoolean();
console.log(randomBool);
