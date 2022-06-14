# HTML

- HyperText Markup Language

- Hiper Texto ? 
- Marcação
 - tags
 - atributos 
- linguagem
 - Maneira correta de escrever 

 https://gist.githubusercontent.com/maykbrito/0acdf4ce919838ffed50915a31fc5b23/raw/6f4dd01ec3116428ec4c99255944cb9ac7927590/cristal-ball.svg

Principios de Javascript
 1. variáveis
 let estaChivendo = true;
 const meuNome = "Gabriel";

 2. tipos de Dados
 Sting
 ""
 ''

 3. namber
 12 - integer ( + -)
 3.2 float (+ - )

 4. boolean
 true ou false
 const estaChovendo = false

 5. undefined
 indefinido <----

 6. atribuição
 atribui valores ( ex: = )

 Aritmeticos (ex: + - * / %)

 Concatenação de string (+)

 Comparação (ex: > < ==)  
 transforma a exprssão em true ou false 

 7. Condicional(if/else)
 ex:
    const idade = 17
    const maiorDeDezoito = idade >= 18

    if(maiorDeDezoito) {
      alert("Pode tirar a carteira de motorista ")
    } else {
      alert("Não pode tirar")
    }

  8. Estrutura de Dados
  Array - Vetor - Lista    
  ex:               0   1   2   3 <-- indíce
    const idades = [2, 16, 17, 20]  

8. Object
const pessoa = {
  nome:""
  endereço:""
  filhos: ["","","",""]
}
Acessar o objeto --> console.log(pessoa.filhos[indíce])

9. Function
ex:
  Function 'nome da função' () {
   
  }

10. Extensões da linguagem (ex: Math, Date)
Math.randow() numeros aleatorio ente o e 1
Math.floor() arredonda numeros quebrados pra baixo
Math.ceil() arredonda numeros quebrados pra cima
Math.PI() numero do PI

11. DOM --> Document, Object, model
window
window.alert("Alerta")
Document
Document.write("Texto")
manipular elementos
document.documentElement.style.background = "Black"