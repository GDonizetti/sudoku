# Sudoku Solver 🧩

Olá! Este é o meu projeto de Sudoku, desenvolvido como parte de um desafio prático proposto pela DIO. O objetivo central foi aplicar e aprimorar meus conhecimentos em lógica de programação, estruturas de dados e algoritmos para criar uma solução robusta para o clássico jogo Sudoku, com foco especial na inicialização e manipulação de tabuleiros.

## 🎯 Objetivo do Projeto

Meu principal objetivo com este projeto foi desenvolver um sistema capaz de:

* **Inicializar um tabuleiro de Sudoku** de forma flexível, aceitando dados de entrada que especificam a posição, o valor e a natureza (fixa ou modificável) de cada célula.
* **Representar visualmente o tabuleiro** no console, garantindo clareza e facilidade de leitura.
* **Validar as regras do Sudoku**, assegurando que as entradas iniciais e eventuais jogadas sigam as restrições do jogo.
* [**OPCIONAL - Adicione se o seu projeto faz isso:** Implementar um algoritmo de resolução para encontrar a solução de qualquer tabuleiro de Sudoku válido, utilizando técnicas como o backtracking.]

## ✨ Funcionalidades Implementadas

* **Inicialização Dinâmica do Tabuleiro:** O projeto aceita uma string de argumentos no formato `x,y;valor,fixo` para configurar o estado inicial do tabuleiro. Isso permite testar diferentes cenários e dificuldades de Sudoku.
    * Exemplo: `0,0;4,false 1,0;7,false ...` (como nos argumentos que você forneceu).
* **Representação Clara em Console:** Desenvolvi uma forma visualmente amigável de exibir o tabuleiro no console, facilitando a visualização do estado atual do jogo.
* **Validação de Regras:** Incluí a lógica para verificar se um número pode ser inserido em uma célula específica, respeitando as regras de linhas, colunas e blocos 3x3.
* [**OPCIONAL - Adicione se o seu projeto faz isso:** **Algoritmo de Resolução (Backtracking):** Implementei um algoritmo de backtracking que percorre o tabuleiro, testando possibilidades até encontrar uma solução válida, ou determinando que o tabuleiro é insolúvel.]
* [**OPCIONAL - Adicione outras funcionalidades que você tenha desenvolvido:** Ex: "Interatividade básica para o usuário tentar preencher células (se for o caso de ser um jogo interativo em console)", "Tratamento de entradas inválidas e mensagens de erro claras."]

## 🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando as seguintes tecnologias:

* **Linguagem:** [PREENCHA AQUI: Ex: `Python`]
* **Ferramentas:**
    * `Git` para controle de versão.
    * `GitHub` para hospedagem do repositório e gerenciamento do projeto.
    * [PREENCHA AQUI: Adicione qualquer outra ferramenta ou IDE que você usou, ex: `VS Code`, `IntelliJ IDEA`, etc.]

## 🚀 Como Rodar o Projeto

Para executar este projeto em sua máquina local, siga os passos abaixo:

**Pré-requisitos:**

* [PREENCHA AQUI: Ex: `Python` (versão 3.x instalada)]

**Instruções:**

1.  **Clone o repositório para sua máquina:**

    ```bash
    git clone [COLE AQUI A URL DO SEU REPOSITÓRIO SUDOKU NO GITHUB]
    ```

2.  **Navegue até o diretório do projeto:**

    ```bash
    cd [NOME DA PASTA DO SEU PROJETO APÓS O CLONE, ex: `sudoku-solver`]
    ```

3.  **Execute o programa passando os argumentos do tabuleiro:**

    Utilize o seguinte comando, substituindo `[SEU_ARQUIVO_PRINCIPAL]` pelo nome do seu arquivo principal (ex: `main.py`, `sudoku.py`).

    ```bash
    # Exemplo de execução em Python:
    python [SEU_ARQUIVO_PRINCIPAL] \
    "0,0;4,false 1,0;7,false 2,0;9,true 3,0;5,false 4,0;8,true 5,0;6,true 6,0;2,true 7,0;3,false 8,0;1,false 0,1;1,false 1,1;3,true 2,1;5,false 3,1;4,false 4,1;7,true 5,1;2,false 6,1;8,false 7,1;9,true 8,1;6,true 0,2;2,false 1,2;6,true 2,2;8,false 3,2;9,false 4,2;1,true 5,2;3,false 6,2;7,false 7,2;4,false 8,2;5,true 0,3;5,true 1,3;1,false 2,3;3,true 3,3;7,false 4,3;6,false 5,3;4,false 6,3;9,false 7,3;8,true 8,3;2,false 0,4;8,false 1,4;9,true 2,4;7,false 3,4;1,true 4,4;2,true 5,4;5,true 6,4;3,false 7,4;6,true 8,4;4,false 0,5;6,false 1,5;4,true 2,5;2,false 3,5;3,false 4,5;9,false 5,5;8,false 6,5;1,true 7,5;5,false 8,5;7,true 0,6;7,true 1,6;5,false 2,6;4,false 3,6;2,false 4,6;3,true 5,6;9,false 6,6;6,false 7,6;1,true 8,6;8,false 0,7;9,true 1,7;8,true 2,7;1,false 3,7;6,false 4,7;4,true 5,7;7,false 6,7;5,false 7,7;2,true 8,7;3,false 0,8;3,false 1,8;2,false 2,8;6,true 3,8;8,true 4,8;5,true 5,8;1,false 6,8;4,true 7,8;7,false 8,8;9,false"
    ```

    Após a execução, [PREENCHA AQUI: descreva o que o usuário verá. Ex: "o tabuleiro de Sudoku inicial será exibido no console, seguido pela sua solução, se encontrada."]

## 💡 Melhorias e Evoluções

Este projeto foi uma ótima oportunidade para aplicar e aprofundar meus conhecimentos. Além da funcionalidade básica, implementei as seguintes melhorias:

* **Robustez na Entrada:** Aprimorei o tratamento dos argumentos de linha de comando para garantir que mesmo entradas complexas ou com espaços sejam corretamente parseadas.
* **Validação Detalhada:** Refinei a lógica de validação para não apenas verificar a validade das regras do Sudoku (linhas, colunas, blocos), mas também para fornecer feedback útil sobre a natureza de qualquer violação.
* **Clareza Visual:** Dediquei tempo para formatar a saída do console de forma a tornar o tabuleiro o mais legível possível, facilitando o acompanhamento do estado do jogo.
* [**OPCIONAL - Se você otimizou o algoritmo:** **Otimização do Algoritmo de Resolução:** Para o algoritmo de backtracking, explorei e implementei técnicas para otimizar a busca pela solução, como a seleção da célula com o menor número de possibilidades (`MRV - Minimum Remaining Values`) para acelerar o processo.]
* [**OPCIONAL - Se você adicionou outros recursos:** **Geração de Tabuleiros:** Experimentei a implementação de um gerador de tabuleiros Sudoku aleatórios com níveis de dificuldade configuráveis, aumentando a capacidade de uso do projeto para além de apenas resolver tabuleiros pré-definidos.]

## 🔗 Links Importantes

* **Contexto do Desafio DIO:** [Se você quiser, adicione um link para a página ou repositório de referência do desafio da DIO]
* **Conceitos de Sudoku:** [Opcional: Link para um bom recurso que explica as regras do Sudoku.]
* **Sobre o Algoritmo de Backtracking:** [Opcional: Link para um artigo ou vídeo que explique o algoritmo de backtracking, caso seu projeto o utilize para resolver.]

## 🤝 Contribuições

Este projeto foi desenvolvido com o intuito de aprendizado e prática. Fico feliz em receber sugestões, relatórios de bugs ou pull requests que possam aprimorar ainda mais este `Sudoku Solver`.

## 📄 Licença

Este projeto está licenciado sob a [PREENCHA AQUI: Ex: `MIT License` ou `Apache License 2.0`]. Para mais detalhes, consulte o arquivo `LICENSE` no repositório.

---

Feito com ❤️ e muito código para a comunidade DIO.
