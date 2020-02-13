# capitalIndex

### Code for finding an index of capital letter

```
capitals (word) {
 let arrIndex = []
 for (let i=0; i < word.length; i++) {
   if(word[i] === word[i].toUpperCase()){
     arrIndex.push(i)
   }
 }
 return arrIndex;
}
```
