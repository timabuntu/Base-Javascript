# Curso JavaScript

Curso Livre da Rocketseat

## <a name="indice">Índice</a>

1.  [Introdução](#parte1)
2.  [Configurando ambiente](#parte2)
3.  [Variáveis e dados](#parte3)
4.  [Operações matemáticas](#parte4)
5.  [Funções](#parte5)
6.  [Condicionais](#parte6)
7.  [Operadores lógicos](#parte7)
8.  [Condição ternária](#parte8)
9.  [Estruturas de repetição](#parte9)
10. [Intervalo e timeout](#parte10)
11. [Desafio](#parte11)
12. [Eventos inline](#parte12)
13. [Trabalhando com a DOM](#parte13)
14. [Lidando com elementos](#parte14)
15. [Alterando estilos](#parte15)
16. [Desafio](#parte16)
17. [Estrutura do app](#parte17)
18. [Iniciando aplicação](#parte18)
19. [Renderizando todos](#parte19)
20. [Criando todos](#parte20)
21. [Excluindo todos](#parte21)
22. [Salvando no storage](#parte22)
23. [Requisições AJAX](#parte23)
24. [Promises](#parte24)
25. [Utilizando Axios](#parte25)
26. [Desafio](#parte26)

---

## <a name="parte1">1 - Introdução</a>

[Voltar ao Índice](#indice)

---

## <a name="parte2">2 - Configurando ambiente</a>

[Voltar ao Índice](#indice)

---

## <a name="parte3">3 - Variáveis e dados</a>

```javascript
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Curso JavaScript - Rocketseat</title>
</head>
<body>

    <script>
    let nome = "José";
    let idade = 34;
    let peso = 90.3;
    let humano = true;

    let alunos = ['jose','marcos','joão'];
    let aluno = {
        nome: alunos[0],
        idade: 20,
        peso: 80.8,
        humano: true,
    }
    console.log(alunos);
    console.log(alunos[1]);

    console.log(aluno.nome);
    console.log(aluno.peso);
    </script>
</body>
</html>
```

[Voltar ao Índice](#indice)

---

## <a name="parte4">4 - Operações matemáticas</a>

```javascript
<!DOCTYPE html>
<html lang="en">

<head>
  <title>Curso JavaScript - Rocketseat</title>
</head>

<body>

  <script>
    let x = 10, y = 5;

    let resultado = x % y;

    x += 3;

    console.log(resultado);
    console.log(x);
  </script>
</body>

</html>
```

[Voltar ao Índice](#indice)

---

## <a name="parte5">5 - Funções</a>

```javascript
<!DOCTYPE html>
<html lang="en">

<head>
  <title>Curso JavaScript - Rocketseat</title>
</head>

<body>

  <script>
    function soma(numero1, numero2) {
      let resultado = numero1 + numero2;
      return resultado;
    }
    let resultado = soma(10, 200);
    console.log(resultado);
  </script>
</body>

</html>
```

[Voltar ao Índice](#indice)

---

## <a name="parte6">6 - Condicionais</a>

```javascript
<!DOCTYPE html>
<html lang="en">

<head>
  <title>Curso JavaScript - Rocketseat</title>
</head>

<body>

  <script>
    function retornoSexo(sexo) {
      // M , F
      /*if(sexo === 'M'){
          return 'Masculino';
      }else if(sexo === 'F'){
          return 'Masculino';
      }else{
          return 'outro';
      }*/

      switch (sexo) {
        case 'M':
          return 'Masculino';
        case 'F':
          return 'Feminino';
        default:
          return 'outro';
      }
    }
    let resultado = retornoSexo('M');
    console.log(resultado);
  </script>
</body>

</html>
```

[Voltar ao Índice](#indice)

---

## <a name="parte7">7 - Operadores lógicos</a>

```javascript
<!DOCTYPE html>
<html lang="en">

<head>
  <title>Curso JavaScript - Rocketseat</title>
</head>

<body>

  <script>
  // AND(&&) , OR (||), NOT (!==)
  let sexo = 'M', idade = 23;

/*if (sexo === 'M' || idade >= 18){
    console.log('ok');
}*/

let masculino = sexo === 'M'; // true
console.log(masculino);
  </script>
</body>

</html>

```

[Voltar ao Índice](#indice)

---

## <a name="parte8">8 - Condição ternária</a>

```javascript
<!DOCTYPE html>
<html lang="en">

<head>
  <title>Curso JavaScript - Rocketseat</title>
</head>

<body>

  <script>
    let sexo = 'M';

    let retorno = (sexo === 'M') ? 'Masculino' : 'Feminino';

    console.log(retorno);
  </script>
</body>

</html>
```

[Voltar ao Índice](#indice)

---

## <a name="parte9">9 - Estruturas de repetição</a>

```javascript
<!DOCTYPE html>
<html lang="en">

<head>
  <title>Curso JavaScript - Rocketseat</title>
</head>

<body>

  <script>
        // for , while

        /*for (let i = 0; i <= 100 ;  i++){
            console.log(i);
        }*/

        let j = 12344141;
        while (j > 50){
            console.log(j);
            j /= 5;
        }
  </script>
</body>

</html>
```
[Voltar ao Índice](#indice)

---

## <a name="parte10">10 - Intervalo e timeout</a>

```javascript
<!DOCTYPE html>
<html lang="en">

<head>
  <title>Curso JavaScript - Rocketseat</title>
</head>

<body>

  <script>
    function exibeAlgo(){
            console.log("Vamo que vamo!");
        }
        // intervalos
        //setInterval(exibeAlgo(), 1000)

        // atrasa
        setTimeout(exibeAlgo, 2000)
  </script>
</body>

</html>
```


[Voltar ao Índice](#indice)

---

## <a name="parte11">11 - Desafio</a>

#####Concluído!!!

[Voltar ao Índice](#indice)

---

## <a name="parte12">12 - Eventos inline</a>

[Voltar ao Índice](#indice)

---

## <a name="parte13">13 - Trabalhando com a DOM</a>

[Voltar ao Índice](#indice)

---

## <a name="parte14">14 - Lidando com elementos</a>

[Voltar ao Índice](#indice)

---

## <a name="parte15">15 - Alterando estilos</a>

[Voltar ao Índice](#indice)

---

## <a name="parte16">16 - Desafio</a>

[Voltar ao Índice](#indice)

---

## <a name="parte17">17 - Estrutura do app</a>

[Voltar ao Índice](#indice)

---

## <a name="parte18">18 - Iniciando aplicação</a>

[Voltar ao Índice](#indice)

---

## <a name="parte19">19 - Renderizando todos</a>

[Voltar ao Índice](#indice)

---

## <a name="parte20">20 - Criando todos</a>

[Voltar ao Índice](#indice)

---

## <a name="parte21">21 - Excluindo todos</a>

[Voltar ao Índice](#indice)

---

## <a name="parte22">22 - Salvando no storage</a>

[Voltar ao Índice](#indice)

---

## <a name="parte23">23 - Requisições AJAX</a>

[Voltar ao Índice](#indice)

---

## <a name="parte24">24 - Promises</a>

[Voltar ao Índice](#indice)

---

## <a name="parte25">25 - Utilizando Axios</a>

[Voltar ao Índice](#indice)

---

## <a name="parte26">26 - Desafio</a>

[Voltar ao Índice](#indice)
