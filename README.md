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

</details>
<details>
  <summary>Kyu 5</summary>

  Aqui poner los katas

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
