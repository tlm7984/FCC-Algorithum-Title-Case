//# FCC-Algorithum-Title-Case
//J.S. Function 

function titleCase(str) {
  words= str.toLowerCase().split(" ");
  for (var i =0; i<words.length;i++){
    var firstLetter=words[i].split("");
    firstLetter[0]=firstLetter[0].toUpperCase();
    words[i]=firstLetter.join("");
  }
  return words.join(" ");
}

titleCase("I'm a little tea pot");
