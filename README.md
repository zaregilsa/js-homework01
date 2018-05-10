# js-homework01
var Str = prompt("Введите фразу: ");

function revStr(Str){
var arrayStr = Str.split([]).reverse().join('');
var countWord = Str.split(" ").length;
//var _Str = Str.replace(/\s/g,  "_");
var Str_ = Str.split(" ").join("_");

alert(arrayStr);
console.log(countWord);
return(Str_);
}
