# OLGA SHKABURA
## CONTACT

* Location: Belarus
* Email: <olgashkabura@gmail.ru>
* GitHub: [olgareuts](https://github.com/olgareuts)

***

## EDUCATION

* Minsk State Higher Radioengineering College  
  Bachelor of Computer science

* THE ROLLING SCOPES SCHOOL  
  JS/FE PRE-SCHOOL 2022Q4 (JAVASCRIPT) certificate of completion

***

## ABOUT ME

I like programming, it fascinates me. I study new tehnologies and improve my skills.

***

## SKILLS

* HTML
* CSS
* JAVASCRIPT
* SQL
* GIT, GITHUB

***

## CODE EXAMPLE

```
function convert(input, source, target) {
  let dec = 0;  
  let result = ''; 
  for (let i = 0; i < input.length; i++) {
    dec+= source.indexOf(input[i]) * Math.pow(source.length, input.length - 1 - i);
  }
  while (dec > 0) {
    result = target[dec % target.length] + result;
    dec = Math.floor(dec / target.length);
  } 
  if (!result) {
    result = target[0];
  }
  return result; 
}
```

***

## LANGUAGES
Russian - Native  

English - Pre-Intermediate

***