# Hi! <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Hi.gif" width="35" />
<p align="center">

<a href="https://linkedin.com/in/rodrigo-neris" target="blank"><img align="center" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>&nbsp;
<a href="https://www.instagram.com/rodrigonerisoficial" target="blank"><img align="center" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>&nbsp;
<a href="https://github.com/rodrigonerisalves" target="blank"><img align="center" src="	https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>&nbsp;
<a href="https://api.whatsapp.com/send?phone=5566999778020" target="blank"><img align="center" src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=whitee" /></a>&nbsp;
<a href="mailto:programadorrodrigonerisalves@gmail.com" target="blank"><img align="center" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>&nbsp;
	
</p> 

### Projeto é criar um sistema que calcule os juros:

A proposta desse projeto é criar um sistema que calcule os juros de uma dívida com base no número de dias passados. Isso será feito utilizando conteúdos que aprendemos em JavaScript.

**Parte 1:**
A primeira parte do código é responsável por importar o módulo `readline-sync`, que permite a leitura de entrada de dados do usuário, e imprimir uma mensagem de introdução ao projeto.

```javascript
const entradaDados = require('readline-sync');
console.log("\n*************************");
console.log("A proposta desse projeto é criar um sistema que calcule os juros\nde uma dívida com base no número de dias passados.\nIsso será feito utilizando conteúdos que aprendemos em JavaScript.");
console.log("*************************");
console.log("\nAplicação de Juros: ");
```

**Parte 2:**
Na segunda parte, o código solicita ao usuário que informe o valor da dívida. Em seguida, verifica se o valor informado é maior que zero.

```javascript
let valor_juros;
let valor_divida = entradaDados.question("\nInforme o valor devido: R$ ");

if(valor_divida > 0)
{
    // código continua aqui
}
else
{
    console.log("O valor da dívida deve ser maior que zero!");
}
```

**Parte 3:**
A terceira parte é responsável por solicitar ao usuário o número de dias passados desde o vencimento do boleto. Em seguida, verifica se o valor informado é maior que zero.

```javascript
let dias_vencimento = entradaDados.question("Informe quantos dias se passaram desde o vencimento do boleto: ");

if(dias_vencimento > 0)
{
    if(dias_vencimento > 15)
    {
        valor_juros = 10;
    }
    else
    {
        valor_juros = 5;
    }

    valor_divida = Number(valor_divida);
    dias_vencimento = Number(dias_vencimento);

    let total_juros = (valor_divida / 100) * valor_juros;
    let valor_total = valor_divida + total_juros;

    console.log("\n--------------------------------------\nValor original da dívida: R$ "+valor_divida);
    console.log("Dias atrasados: "+dias_vencimento);
    console.log("Taxa de Juros: "+valor_juros+"%");
    console.log("Valor total com juros: R$ "+valor_total);
    console.log("--------------------------------------");
}
else
{
    console.log("Você está em dia!");
}
```

Dessa forma, o código é dividido em três partes: a primeira apresenta a descrição do projeto, a segunda solicita o valor da dívida e a terceira solicita o número de dias passados desde o vencimento do boleto e realiza o cálculo dos juros, caso o valor seja maior que zero.

## Tecnologias que uso no meu dia.
<div style= "display: inline_block"><br/>
      <img align="center" alt="PYTHN" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
      <img align="center" alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
      <img align="center" alt="CSS" src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white" /> 
      <img align="center" alt="JAVA" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" /> 
      <img align="center" alt="JAVASCRIPT" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" /> 
      <img align="center" alt="TYPESCRIPT" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" /> 
      <img align="center" alt="KOTLIN" src="https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white" /> 
      <img align="center" alt="MSQL" src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" /> 
        <img align="center" alt="MSQL" src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" /> 
      <img align="center" alt="MSQL" src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white" />       

</div>

![](https://camo.githubusercontent.com/992babdffd8c74a1502de375fbdf7e4d54773242/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f53576f536b4e36447854737a71494b4571762f67697068792e676966)

### <img src='https://media1.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif?cid=ecf05e47x2g034i9pzwtzzsd3xgg2w9nr94t4tflbbgo3008&rid=giphy.gif' width='25' /> My Github Stats:
![Apoorv's github stats](https://github-readme-stats.vercel.app/api?username=rodrigonerisalves&show_icons=true&title_color=ffc857&icon_color=8ac926&text_color=daf7dc&bg_color=151515&hide=issues&count_private=true&include_all_commits=true)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=rodrigonerisalves&layout=compact&text_color=daf7dc&bg_color=151515&hide=css,html,php)](https://github.com/rodrigonerisalves)
[![GitHub Streak](https://streak-stats.demolab.com/?user=rodrigonerisalves&theme=dark)](https://github.com/rodrigonerisalves)

---