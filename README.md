abntex2-ftec
=========================

## Informações Gerais
Classe que adapta o pacote abntex2 para as normas da FTEC. O abntex2 (http://www.abntex.net.br/) é uma classe que implementa as normas da ABNT para os usuários LaTex.

Estão disponíveis os seguintes arquivos para download:
- ftec-abntex2.cls         `Pacote com as regras gerais do template`
- Graduacao.sty             `Estilo de formatação para os Trabalhos de Conclusão de Curso`
- Apresentacao.tex       `Arquivo apresentando as funcionalidades do modelo`
- Modelo_TCC.tex      `Modelo para os Trabalhos de Conclusão de Curso`
- Bibliografia.bib   `Arquivo com a bibliografia base dos modelos, a ser personalizada`



Sugerimos escrever documentos por cima do arquivo de modelo .tex fornecido, com toda sua estrutura de pastas. Pra quem utilizar outro modelo, é preciso colocar a classe adequada:

```latex
\documentclass[
	% -- opções das classes --
    % (...)
	]{ftec-abntex2}
```

Com relação ao pacote abntex2, foram modificadas as seguintes páginas:
- Fontes -> Times New Roman
- Sumário -> Tradicional, com hierarquia entre capítulos e seções
- Listas -> Ilustrações, Tabelas, Quadros e Códigos
- Capa -> Imagens da Faculdade de Engenharia da FTEC adicionadas
- Folha de rosto
- Ficha catalográfica
- Folha de Aprovação

## Pacotes

Lista mínima de pacotes a serem instalados em distribuições Ubuntu/Mint linux
* texlive
* texlive-base
* texlive-latex-base
* abntex
* texlive-fonts-recommended
* texlive-fonts-extra
* texlive-lang-portuguese
* texlive-latex-recommended
* texlive-science
* texlive-publishers
* texlive-latex-extra
* preview-latex-style
* texlive-pictures
* texlive-font-utils

## Ambiente de desenvolvimento
1. Linux
  * Instalar os pacotes listados anteriormente
  * Escolher uma IDE para latex

2. Windows
  * Instalar o miktex
  * Escolher uma IDE para latex

3. Online
  * https://www.overleaf.com/ , https://papeeria.com/ ou https://cocalc.com/doc/latex-editor.html
  * Ambientes online com todos os pacotes latex existentes já prontos para uso, com a opção de compartilhamento de projeto entre várias pessoas
  * Para usar nosso template, basta importar a estrutura de pastas e compilar o texto