# Projeto-DIO-Criando-Jogo-Sudoku-Java

:spiral_calendar: Atualizado em 26 de Junho de 2025 :heart:

<img align="right" alt="GIF" height="160px" src="https://github.com/rdeconti/rdeconti-resources/blob/main/Digital%20Innovation%20One%20-%20Logotipo.png" />

Este projeto foi proposto pela Digital Innovation One
- Link do código original: 
-  ** Brach main com jogo no terminal: https://github.com/digitalinnovationone/sudoku
-  ** Branch com interface gráfica: https://github.com/digitalinnovationone/sudoku/tree/ui
- Professor: José Luiz Abreu Cardoso Junior
- Aulas: [DIO](https://web.dio.me/lab/criando-um-jogo-do-sudoku/learning/2bb0ec4c-a3a7-4358-a6b2-9bf47ab13eda?back=/track/tonnie-java-and-ai-europe)

## Descrição
- Neste desafio, você será responsável por criar um jogo de Sudoku em Java, implementando funcionalidades essenciais para um jogo interativo e funcional no terminal. O objetivo é consolidar seus conhecimentos em programação orientada a objetos, manipulação de estruturas de dados, uso de métodos e classes, além de lidar com entradas e saídas no terminal.

## Estrutura das Pastas
Este repositório contém a implementação de um jogo de Sudoku em Java, dividido em dois módulos principais:

- **sudoku-master**  
  Este módulo contém a versão de linha de comando (console) do jogo Sudoku.  
  - Implementa toda a lógica do jogo, manipulação do tabuleiro, regras e interação via terminal.
  - Arquivo principal: [`Main.java`](sudoku-master/src/br/com/dio/Main.java)
  - Outras classes importantes: [`Board.java`](sudoku-master/src/br/com/dio/model/Board.java), [`Space.java`](sudoku-master/src/br/com/dio/model/Space.java), [`GameStatusEnum.java`](sudoku-master/src/br/com/dio/model/GameStatusEnum.java)

- **sudoku-ui**  
  Este módulo traz a interface gráfica (GUI) do Sudoku utilizando Java Swing.  
  - Utiliza a lógica do jogo adaptada para interação visual, com botões, campos de texto e painéis.
  - Arquivo principal: [`UIMain.java`](sudoku-ui/src/br/com/dio/UIMain.java)
  - Componentes customizados: botões, campos de entrada, painéis e telas, localizados em `src/br/com/dio/ui/custom/`
  - Serviços de controle e notificação: `src/br/com/dio/service/`

## Como executar

Cada módulo pode ser executado separadamente, dependendo se você deseja jogar no terminal ou na interface gráfica.

- **Console:**  
  Entre na pasta `sudoku-master` e execute a classe `Main`.

- **Interface Gráfica:**  
  Entre na pasta `sudoku-ui` e execute a classe `UIMain`.

## Links Importantes
- Draw.io: https://app.diagrams.net

    - Argumentos para passar no running do projeto:
        0,0;4,false 1,0;7,false 2,0;9,true 3,0;5,false 4,0;8,true 5,0;6,true 6,0;2,true 7,0;3,false 8,0;1,false 0,1;1,false 1,1;3,true 2,1;5,false 3,1;4,false 4,1;7,true 5,1;2,false 6,1;8,false 7,1;9,true 8,1;6,true 0,2;2,false 1,2;6,true 2,2;8,false 3,2;9,false 4,2;1,true 5,2;3,false 6,2;7,false 7,2;4,false 8,2;5,true 0,3;5,true 1,3;1,false 2,3;3,true 3,3;7,false 4,3;6,false 5,3;4,false 6,3;9,false 7,3;8,true 8,3;2,false 0,4;8,false 1,4;9,true 2,4;7,false 3,4;1,true 4,4;2,true 5,4;5,true 6,4;3,false 7,4;6,true 8,4;4,false 0,5;6,false 1,5;4,true 2,5;2,false 3,5;3,false 4,5;9,false 5,5;8,false 6,5;1,true 7,5;5,false 8,5;7,true 0,6;7,true 1,6;5,false 2,6;4,false 3,6;2,false 4,6;3,true 5,6;9,false 6,6;6,false 7,6;1,true 8,6;8,false 0,7;9,true 1,7;8,true 2,7;1,false 3,7;6,false 4,7;4,true 5,7;7,false 6,7;5,false 7,7;2,true 8,7;3,false 0,8;3,false 1,8;2,false 2,8;6,true 3,8;8,true 4,8;5,true 5,8;1,false 6,8;4,true 7,8;7,false 8,8;9,false

## Licença

MIT License
