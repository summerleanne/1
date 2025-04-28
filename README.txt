var oldstringify=JSON.stringify
JSON.stringify=function(){
return oldstringify.apply(null,arguments).replaceAll("noname","")
}
