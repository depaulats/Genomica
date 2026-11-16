Acesse as ***Notas de Aula em Genômica*** em https://depaulats.github.io/Genomica/


# Genômica 2026/2

Bem-vindo ao repositório oficial da disciplina ***Genômica*** do Instituto de Biologia Roberto Alcantara Gomes (IBRAG) da Universidade do Estado do Rio de Janeiro (UERJ)!

Este espaço foi criado para concentrar todos os recursos necessários para as atividades práticas da disciplina. Aqui você encontrará scripts, ferramentas de bioinformática, conjuntos de dados e instruções detalhadas para auxiliar no seu aprendizado.

Link para a pasta [compartilhada](https://drive.google.com/drive/folders/1F_8FSIkL2gu_zn1-07MG9qrml5RkyR-k?usp=sharing) da disciplina no Google Drive


## Estrutura do Repositório

/aulas: Tutoriais e manuais para apoio durante as aulas práticas

/dados: Contém os conjuntos de dados utilizados nas atividades.

/ferramentas: Lista e instruções de instalação de ferramentas de bioinformática.

/roteiros: Inclui códigos e scripts para análise de dados genômicos.


## Objetivo

O objetivo deste repositório é fornecer um ambiente organizado e de fácil acesso para que os discentes possam:

- Reproduzir análises bioinformáticas;

- Explorar dados genômicos reais;
  
- Desenvolver habilidades práticas em bioinformática.


## Ferramentas Utilizadas

Entre as ferramentas que serão abordadas estão:

- Alinhadores (e.g., [Bowtie2](https://github.com/BenLangmead/bowtie2))

- Visualizadores de genomas (e.g., [IGV](https://igv.org/))

- Softwares para análise de variantes (e.g., [Samtools](https://github.com/samtools/samtools))

- Linguagens como R para análise estatística e manipulação de dados


## Público-Alvo

Discentes matriculados na disciplina de Genômica do IBRAG.


## Como Usar

Clone o repositório em sua máquina local:

    git clone https://github.com/seu-usuario/genomica-2024.git

Siga as instruções específicas de cada atividade disponíveis na pasta correspondente.

Utilize os datasets e scripts conforme orientado durante as aulas.

Qualquer dúvida, entre em contato pelo email do docente ou via [Issues](https://github.com/depaulats/uerj-ibrag-genomica/issues) aqui mesmo no GitHub.

Este repositório é destinado exclusivamente para fins didáticos e é compartilhado pela licença Creative Commons.

Bons estudos!


### Licença de uso

© 2026 Thiago S. de Paula

Este livro está licenciado sob a Licença _Creative Commons_ Atribuição-NãoComercial-CompartilhaIgual 4.0 (CC BY-NC-SA 4.0). Para ver uma cópia desta licença, visite https://creativecommons.org/licenses/by-nc-sa/4.0/.


### Como renderizar o livro

1. Instale **bookdown** com o comando `install.packages("bookdown")`. Se você já o tem, atualize-o para a [última versão](https://CRAN.R-project.org/package=bookdown).

2. Renderize (*render*) localmente com o comando `bookdown::render_book("index.Rmd")`.

3. Use o comando `browseURL("docs/index.html")` para ver o livro localmente (ou simplesmente abra o arquivo `index.html` em um navegador).

4. Se a versão renderizada lhe agrada, comprometa (*commit*) e envie (*push*) todos os arquivos modificados para o GitHub. 

5. Vá ao GitHub, usando o comando `usethis::browse_github()`.

Você precisará repetir os passos 2 e 4 todas as vezes que quiser atualizar o livro online.


### Informações adicionais

As ***Notas de Aula em Genômica*** foi inicialmente gerado a partir de um modelo disponível [aqui](https://github.com/jtr13/bookdown-template).

Por favor consulte o vídeo demostrativo de [como criar um livro **bookdown**](http://bit.ly/fiveminutebookdown) e o [guia oficial do **bookdown**](https://bookdown.org/yihui/bookdown). 


