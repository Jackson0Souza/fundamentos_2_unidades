# type conversion (conversão de tipo) / type coercion (coerção de tipo)

```js

  var x = Number ("0") //type conversion, nessa linha é feita uma conversão de tipo explicita
  var y = "2" + 3 // type coercion, nessa linha é feita uma conversão implicito do valor 3 que é numerico (number) para texto (string).

  //Onde usa expreesões condicional e repetição, faz necessário um valor boolean (true ou false).
  //Ex:
    if(true){
  }

  //Caso não for informado uma expressão ou um valor boolean diretamente, ele fará um Type Coercion (coerção de tipo)
  //Ex:
    if (0){ //Nessa linha ele ira fazer uma conversão do 0 para um boolean (true ou false), nesse caso 0 será falso.}



```

