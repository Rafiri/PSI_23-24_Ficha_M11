# Ficha de Programação e Sistemas de Informação - Módulo 11

Cria um repositório **privado** no GitHub com o nome **"PSI_Ficha_M11"** e com um ficheiro **README**. Faz ***clone*** do mesmo para o teu computador.

Preenche o **README** localmente com as respostas dos exercícios, e seguidamente, faz ***push*** das atualizações.

Para entregar a ficha, acede a [este link](https://docs.google.com/spreadsheets/d/1DrdGnICVAA8q9bs9_LAURFKoReAO7jJGB8qqvUWacL0/edit?usp=sharing) (separador **Ficha Módulo 11**), e mete o **URL** do teu repositório ao lado do teu nome.
No teu repositório, acede a "Settings -> Collaborators" e adiciona o utilizador "Manuel Geraldes" para ter acesso.

## Exercício 1 - Para cada afirmação sobre tratamento de erros em C#, indica se é **Verdadeira** ou **Falsa**. Justifica a tua resposta. (3v)

1. Exceções são usadas para lidar com situações inesperadas que podem ocorrer durante a execução de um programa.V
2. O bloco 'try' é usado para prevenir uma exceção.F- é o bloco catch.
3. Um bloco 'catch' tem de ser sempre usado imediatamente depois de um bloco 'try'.V
4. O bloco 'finally' é sempre executado antes do bloco 'catch', mesmo que uma exceção não seja lançada ou apanhada.V
5. É possível criar exceções customizadas.V
6. O *statement* 'using' é usado para gerir recursos apropriadamente.F

## Exercício 2 - Para cada afirmação sobre manipulação de *streams* em C#, indica se é **Verdadeira** ou **Falsa**. Justifica a tua resposta. (4v)

1. *Streams* são unidirecionais.V
2. As classes StreamReader/StreamWriter são usadas para ler/escrever caracteres de/para uma *stream* em qualquer formato.V
3. Uma stream pode ser fechada de forma explícita ou implícita.V
4. A classe 'GZipStream' é usada tanto para comprimir como descomprimir *streams* de dados.V

## Exercício 3 - Escreve o código necessário para criar um programa em C# de acordo com as seguintes instruções: (7v)

- O programa deve aceitar como único argumento da linha de comandos um nome de ficheiro de texto e imprimir os conteúdos desse ficheiro no ecrã.
- O programa deve tratar separadamente todas as exceções que podem ocorrer quando o ficheiro é aberto para leitura, apresentando uma mensagem de erro adequada em cada caso.
- 
