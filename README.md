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


</details>
<details>
  <summary>Kyu 6</summary>

  Aqui poner los katas

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
