# CodeWars
<details>
  <summary>Kyu 8</summary>

  <details>
  <summary>ASCII Total</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function uniTotal(str) {
  let sum = 0;
  for (let i = 0; i < str.length; i++) {
    sum += str.charCodeAt(i);
  }
  return parseInt(sum);
}
```


</details>
 <details>
  <summary>Square(n) Sum</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function squareSum(numbers){
let result = 0;
  for(i = 0 ; i < numbers.length; i++){
    result += numbers[i] * numbers[i];
    }
  return result;
}
```


</details>
 <details>
  <summary>Exclusive "or" (xor) Logical Operator</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function xor(a, b) {
  return a != b;
}
```


</details>
<details>
  <summary>Function 1 - hello world</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function greet(){
  return "hello world!"
}
```


</details>
<details>
  <summary>All Star Code Challenge #18</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function strCount(str, letter){  
  let count = 0;
  for(i = 0; i < str.length; i++){
    if(str[i] == letter)
      count ++;
  }
  return count;
}
```


</details>
<details>
  <summary>Power</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function numberToPower(number, power){
  let n = 1;
  for(let i = 0; i < power; i++){
   n *= number;
  }
  return n;
}
```


</details>
<details>
  <summary>Counting sheep...</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function countSheeps(arrayOfSheep) {
 let number = 0;
  for(let i = 0; i < arrayOfSheep.length; i++){
    if(arrayOfSheep[i] != null && arrayOfSheep[i] != false)
      number ++;
  }
  return number;
}
```


</details>
<details>
  <summary>String repeat</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function repeatStr (n, s) {
  let str = "";
  for(let i = 0; i < n; i++){
    str += s;
  }
  return str;
}
```


</details>
<details>
  <summary>Find out whether the shape is a cube</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
var cubeChecker = function(volume, side){
  console.log(volume, side);
  if(volume == Math.pow(side, 3) && side > 0)
    return true;
  else
  return false;
};
```


</details>
<details>
  <summary>Chuck Norris VII - True or False? (Beginner)</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function ifChuckSaysSo(){
return 0>1;
}
```


</details>
<details>
  <summary>DNA to RNA Conversion</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function DNAtoRNA(dna) {
  let str = "";
  for(let i = 0; i < dna.length; i++){
    if(dna[i] != "T")
    str += dna[i];
    else
      str += "U";
  }
  return str;
}
```


</details>
<details>
  <summary>Remove String Spaces</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function noSpace(x){
  let str = "";
  for (let i = 0; i < x.length; i++)
  {  
    if(x[i] != " ")
      str += x[i];
  }
  return str;
}
```


</details>
<details>
  <summary>Is your period late?</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function periodIsLate(last, today, cycleLength) {

const diferenciaEnMilisegundos = today.getTime() - last.getTime();
const diferenciaEnDias = Math.floor(diferenciaEnMilisegundos / (1000 * 60 * 60 * 24));
  
  if(diferenciaEnDias > cycleLength)
    {
      return true;
    }
  else
  return false;
}
```


</details>
<details>
  <summary>Simple multiplication</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function simpleMultiplication(number) {
  if(number % 2 == 0)
    return number * 8;
  else
    return number * 9;
}
```


</details>
<details>
  <summary>Determine offspring sex based on genes XX and XY chromosomes</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function chromosomeCheck(sperm) {
  let result = "";
  if(sperm == 'XX')
    result += "Congratulations! You're going to have a daughter.";
  if(sperm == 'XY')
    result += "Congratulations! You're going to have a son.";
  return result;
}
```


</details>
<details>
  <summary>Count of positives / sum of negatives</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function countPositivesSumNegatives(input) {
  if (input === null || input.length === 0) 
    return [];
     
  let positiveCount = 0;
  let negativeCount = 0; 
  
  for(let i = 0; i < input.length; i++)
  {
    if(input[i] > 0)
    {
      positiveCount += 1;
    }
    else if(input[i] < 0)
    {
      negativeCount += input[i];
    }
  }
  return [positiveCount, negativeCount];
}
```


</details>
<details>
  <summary>Count the number of cubes with paint on</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
var countSquares = function(cuts)
{
  if(cuts == 0)
    return 1;
  result = Math.pow((cuts + 1), 3) - Math.pow((cuts - 1), 3)
  return  result;
}
```


</details>
<details>
  <summary>Find Nearest square number</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function nearestSq(n){
  if(Math.sqrt(n) % 1 == 0)
  {
    return n;
  }
  else
  {
    let number;
    number = Math.sqrt(n);
    
    let firstDecimal = Number(number.toString().split('.')[1].charAt(0));
    let result = 0;
    
    if (firstDecimal >= 5) 
    {
    result = (Math.floor(number) + 1) * (Math.floor(number) + 1);
    }
    else
    {
    result = Math.floor(number) * Math.floor(number);
    } 
    return result;
  }
  
} 
```


</details>




</details>
<details>
  <summary>Kyu 7</summary>

 <details>
  <summary>Mispelled word</summary>
<a href="https://imgur.com/fmLaIC2"><img src="https://i.imgur.com/fmLaIC2.png" title="source: imgur.com" /></a>

```javascript
var mispelled = function(word1, word2)
{
  let errors = 0;
  let length = 0;
  if(word1.length > word2.length)
    length = word1.length;
  else
    length = word2.length;
  for (let i = 0; i< length; i++)
  {
    if(word1[i] != word2[i] && word1[i] != word2[i - 1] && word1[i] != word2[i + 1]) 
      errors ++;
  }
  if(errors > 1)
    return false;
  else 
    return true;
}
```


</details>
<details>

  <summary>Divide and Conquer</summary>
  
  
<a href="https://imgur.com/efj7TRp"><img src="https://i.imgur.com/efj7TRp.png" title="source: imgur.com" /></a>
```javascript
function divCon(x)
{
  
  let result = 0;
  let ints = 0;
  let strings = 0;
  
  for(let i = 0; i < x.length; i++)
    {
    if(typeof(x[i]) == "number")
      ints += (x[i]);
    else
      strings += Number(x[i]);
    }
  
  result = ints - strings;
  
  return result;
  
}
```


</details>
 <details>
  <summary>sPoNgEbOb MeMe</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function spongeMeme(sentence) {
  let str = "";
  for(let i = 0; i < sentence.length; i++){
    if(i % 2 == 0){
      str += sentence[i].toUpperCase();
    }
    else{
      str += sentence[i].toLowerCase();
    }
  }
  return str;
}
```


</details>
<details>
  <summary>Complementary DNA</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function DNAStrand(dna)
{
  const obj = { 
    "A": "T", "T": "A", "C": "G", "G": "C"
  }
  let str = "";
  for(let i = 0; i < dna.length; i++)
  {
    str += obj[dna[i]];
  }
  return str;
}
```


</details>
<details>
  <summary>Beginner Series #3 Sum of Numbers</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
  function GetSum( a,b )
{
   if (a == b) return a;
   else if (a < b) return a + GetSum(a+1, b);
   else return a + GetSum(a-1,b);
}
```


</details>
<details>
  <summary>Regex validate PIN code</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function validatePIN (pin) 
{
if (pin.length === 4 || pin.length === 6) {
    if (/^\d+$/.test(pin)) {
      return true;
    }
  }
  return false;
}
```


</details>


</details>
<details>
  <summary>Kyu 6</summary>

  <details>
  <summary>Find the unique number</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
function findUniq(arr) {
  const counts = {};
  
  // Contar la cantidad de veces que aparece cada número
  for(let i = 0; i < arr.length; i++) {
    if(counts[arr[i]]) {
      counts[arr[i]]++;
    } else {
      counts[arr[i]] = 1;
    }
  }
  
  // Buscar la clave con un valor de 1
  for(const num in counts) {
    if(counts[num] === 1) {
      return Number(num);
    }
  }
}
```


</details>
<details>
  <summary>Replace With Alphabet Position</summary>
<a href="https://imgur.com/7u20xV0"><img src="https://i.imgur.com/7u20xV0.png" title="source: imgur.com" /></a>

```javascript
public static class Kata
{
  public static string AlphabetPosition(string text)
  {
  string newStr = "";

  for(int i = 0; i < text.Length; i++) {
    char c = text[i];
    if(c == 'a' || c == 'A')newStr += 1 + " ";
    else if(c == 'b'|| c == 'B')newStr += 2 + " ";
    else if(c == 'c'|| c == 'C')newStr += 3 + " ";
    else if(c == 'd'|| c == 'D')newStr += 4 + " ";
    else if(c == 'e'|| c == 'E')newStr += 5 + " ";
    else if(c == 'f'|| c == 'F')newStr += 6 + " ";
    else if(c == 'g'|| c == 'G')newStr += 7 + " ";
    else if(c == 'h'|| c == 'H')newStr += 8 + " ";
    else if(c == 'i'|| c == 'I')newStr += 9 + " ";
    else if(c == 'j'|| c == 'J')newStr += 10 + " ";
    else if(c == 'k'|| c == 'K')newStr += 11 + " ";
    else if(c == 'l'|| c == 'L')newStr += 12 + " ";
    else if(c == 'm'|| c == 'M')newStr += 13 + " ";
    else if(c == 'n'|| c == 'N')newStr += 14 + " ";
    else if(c == 'o'|| c == 'O')newStr += 15 + " ";
    else if(c == 'p'|| c == 'P')newStr += 16 + " ";
    else if(c == 'q'|| c == 'Q')newStr += 17 + " ";
    else if(c == 'r'|| c == 'R')newStr += 18 + " ";
    else if(c == 's'|| c == 'S')newStr += 19 + " ";
    else if(c == 't'|| c == 'T')newStr += 20 + " ";
    else if(c == 'u'|| c == 'U')newStr += 21 + " ";
    else if(c == 'v'|| c == 'V')newStr += 22 + " ";
    else if(c == 'w'|| c == 'W')newStr += 23 + " ";
    else if(c == 'x'|| c == 'X')newStr += 24 + " ";
    else if(c == 'y'|| c == 'Y')newStr += 25 + " ";
    else if(c == 'z'|| c == 'Z')newStr += 26 + " ";
     
    
  }
    if(newStr.Length > 1)
    {
      
    newStr = newStr.Substring(0, newStr.Length - 1);
    return newStr;
    }
    else
    return newStr;
  }
}
```


</details>

</details>
<details>
  <summary>Kyu 5</summary>

  <details>
  <summary>The Hashtag Generator</summary>
<a href="https://imgur.com/aYMOqFF"><img src="https://i.imgur.com/aYMOqFF.png" title="source: imgur.com" /></a>

```javascript
function generateHashtag (str) {
  if (str.trim().length === 0) {
    return false;
  }
  
  let result = "#";

  for (let i = 0; i < str.length; i++) {
    if (str[i - 1] === " " && str[i] !== " ") {
      result += str[i].toUpperCase();
    } else if (i === 0) {
      result += str[i].toUpperCase();
    } else if (str[i] !== " ") {
      result += str[i];
    }
  }
  if (result.length > 140) {
    return false;
  } else {
    return result;
  }
}
```


</details>


</details>
<details>
  <summary>Kyu 4</summary>

  Aqui poner los katas

</details>
<details>
  <summary>Kyu 3</summary>

  Aqui poner los katas

</details>
<details>
  <summary>Kyu 2</summary>

  Aqui poner los katas

</details>
<details>
  <summary>Kyu 1</summary>

  Aqui poner los katas

</details>
