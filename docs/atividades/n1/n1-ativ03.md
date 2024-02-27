# UPM CC - Computação Visual 07G (2024.1)

***Copyright &copy; 2024 André Kishimoto. Todos os direitos reservados.***

[Home ⤴](../../index.md)

## Semana 3: Online - Teoria (Formatos de imagem)

Atividade em grupo de até 4 pessoas.

### Enunciado

Nessa semana, vimos que os processos de amostragem e quantização são realizados para converter dados contínuos (capturados por sensores de aquisição de imagens) em dados discretos, resultando na geração de imagens digitais.

A discretização converte uma função contínua *f(s, t)* em uma matriz bidimensional *f(x, y)* com *MxN* elementos, sendo:
- *M*: Número de linhas da imagem.
- *N*: Número de colunas da imagem.
- *(x, y)*: Coordenadas discretas.
- *x* = 0, 1, 2, ..., *M* – 1.
- *y* = 0, 1, 2, ..., *N* – 1.

Cada elemento da matriz bidimensional (e da imagem digital) corresponde a um pixel.

No entanto, quando trabalhamos com arquivos de imagem (isto é, o conteúdo desses arquivos é interpretado como a representação de uma imagem digital), eles raramente armazenam apenas as informações dos pixels que formam a imagem.

**Sabendo disso, escolha um formato de arquivo de imagem e descreva como o conteúdo do arquivo é organizado. Na descrição, detalhe as principais seções do formato de arquivo de imagem escolhido.**

Lembre-se de incluir todas as referências consultadas (livros, links de artigos, vídeos, etc.) e identificar todas as pessoas do grupo.

Publique o resultado dessa atividade no blog.

**Dica:**<br>
O livro "Encyclopedia of Graphics File Formats" (Murray e vanRyper, 1996) é uma ótima referência e está disponível online sob licença Creative Commons.

### Desafio opcional

Desenvolva um programa em C que lê o conteúdo de um arquivo no formato da imagem escolhida por você e exibe todas as informações do arquivo (assinatura, cabeçalho, dados, etc.) em modo texto.

Disponibilize o código-fonte em um repositório git público.

### Desafio opcional++

Incremente o programa do desafio anterior, de forma que o programa exiba a imagem (pixels) na tela.

Disponibilize o código-fonte em um repositório git público.
### Entrega

- **Quando?** Entregar até **10/03/2024 23:59**
- **Como?** Uma pessoa integrante do grupo deve enviar um e-mail para o professor com as informações a seguir:
    - **Assunto** (por favor, coloque exatamente esse texto no assunto do e-mail!): **[CompVis07G-2024-1] Entrega da atividade: Semana 3 (Formatos de imagem)**
    - **Corpo do e-mail**: inclua a URL de onde o resultado desta atividade foi publicado (incluindo os desafios opcionais, caso aplicável).
