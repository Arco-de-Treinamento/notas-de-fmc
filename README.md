<p align="center">
  <img src = "res/img/chaos.png" style = "width: 20%;">
</p>
<h1 align = "center"> 
  Notas de Jubilado - Matemática Elementar
 
  
  <p align="center">
    <img src="https://img.shields.io/github/last-commit/JosManoel/notas-de-jubilado">
    <img src="https://img.shields.io/github/license/JosManoel/notas-de-jubilado">
    <img src="https://img.shields.io/github/downloads/JosManoel/notas-de-jubilado/total">
  </p>
</h1>

<p align ="center">
<a href= "#sobre-este-projeto">👨🏻‍💻 Sobre este projeto</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
<a href="#consideracoes">📋 Considerações</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
<a href="#desenvolvimento">💻 Compilação</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
<a href="#referecias">📚 Referências</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
<a href="#licenca">📝 Licença</a>
</p>

***

<h2 id = "sobre-este-projeto">👨🏻‍💻 Sobre este projeto</h2>

Esse repositório mantém as notas de jubilado da disciplina Matemática Elementar do Bacharelado em Tecnologia da Informação da Universidade Federal do Rio Grande do Norte.

As **"Notas de Jubilado"** não são um material oficial da matéria, sendo estritamente uma **paródia** das [notas de aula](https://github.com/matematica-elementar/notas-de-aula) oficiais, construídas com o intuito de descontrair durante os estudos da matemática discreta. Em hipótese nenhuma utilize esse artigo como única fonte de conhecimento.

_Considere-se avisado..._

_Lembre-se que existe um motivo para esse título..._


***

<h2 id="consideracoes">📋 Considerações</h2>

Decidi criar o Notas de Jubilado como uma forma de aprender um pouco de [LaTeX](https://pt.wikipedia.org/wiki/LaTeX) e, simultaneamente, estudar matemática discreta. Como estava tendo dificuldade com alguns tópicos do tema no método de ensino convencional, recorri ao ["Learn In Public"](https://segredo.dev/aprenda-em-publico/), uma modalidade de estudo onde ocorre a produção ativa de conteúdo, ao invés do simples consumo passivo que estamos habituados. 

Neste projeto eu também tentarei responder algumas perguntas recorrentes nos meus núcleos de conversa. A matemática discreta tende a parecer desnecessariamente complicada para um recém-iniciado na área. Por vezes surgiam questionamentos como **"pra quê estou estudando isso?"** ou **"cadê o código?"**. Sendo assim, a cada capítulo também existirá um tópico referente a uma aplicação do tema na ciência da computação.

É importante ressaltar que, como você, caro leitor curioso, eu também sou um estudante lascado. Por isso, o desenvolvimento do material seguirá o insano ritmo de aprendizado de um universitário brasileiro. 


***

<h2 id="compilacao">💻 Compilação</h2>

Assim como nas notas de aula, as notas de jubilado utilizam o LaTeX para produzir o material. Desde modo, caso você seja louco o suficiente para estudar o tema ao nível de código, será necessário que alguma distribuição TeX, como o [TexLive](https://tug.org/texlive/), e o utilitário [GNU Make](https://www.gnu.org/software/make/) estejam instalados em sua máquina.

Certifique-se de também possuir o [Biber](https://biblatex-biber.sourceforge.net/), para que o sumário e as citações possam funcionar corretamente, e o [Pygments](https://pygments.org/), para que possa incluir trechos de código no documento em formato de snippet.

> Note que para a utilização do Pygments e do package Minted é necessário a adição da flag **-shell-escape**. Para mais informações consulte a [documentação](https://github.com/gpoore/minted/blob/master/source/minted.pdf).

Assim como de costume, para compilar o projeto e gerar um documento em formato pdf basta utilizar o comando abaixo:

```sh
make
```

Caso queira compilar e automaticamente abrir o arquivo em seu leitor de pdf local, utilize o seguinte comando:

```sh
make view
```

Existe ainda a possibilidade de eliminar todos os arquivos gerados pela última compilação, incluindo o pdf. Para esse caso sugerimos que opte por:

```sh
make cleanall
```

> Note que ao compilar o documento também será realizada a atualização das macros utilizadas no projeto, hospedadas no [GitHub](https://github.com/matematica-elementar/macros).

> Você também pode testar sua sanidade em um ambiente Windows. Nesse caso recomendo que leia um pouco sobre o [WSL](https://learn.microsoft.com/pt-br/windows/wsl/install).

***

<h2 id="referencias">📚 Referências</h2>

* [Notas de Aula - Matemática Elementar](https://github.com/matematica-elementar/notas-de-aula)


***

<h2 id="licenca">📝 Licença</h2>

- Este projeto está sob a licença [MIT](https://github.com/JosManoel/notas-de-jubilado/blob/main/LICENSE).

***

<div align = "center">

  👋 Feito por [JosManoel](https://github.com/JosManoel) com ☕ , 💊 , 💻 e mais um pouco de ☕.

</div> 
