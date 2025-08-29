<div align="center">

Em Busca da Verdade
</div>

Um RPG de sobrevivência em Python onde você acorda em um mundo devastado e precisa lutar contra fome, sede, inimigos e mudanças climáticas. A jornada começa em 06/12/1994, aos 18 anos. Se conseguir viver até os 30, lembranças de sua família voltarão e a verdade será revelada.

Principais Recursos
Narrativa e Tela Inicial: Introdução à história e menu com escolhas iniciais.

Inventário Completo: Gerenciamento de itens, consumo de recursos e sistema de crafting.

Sistema de Combate e Sobrevivência: Enfrente inimigos, resista ao clima e ao passar do tempo.

Destaque Técnico: API de Save/Load Local
Para melhorar a experiência do jogador, foi implementada uma API local que salva e carrega o progresso do jogo usando um arquivo JSON.

Como Funciona: A API gerencia o estado atual do jogo — incluindo as estatísticas do jogador, inventário e progresso na história — salvando tudo em um arquivo savegame.json.

Persistência: Ao iniciar o jogo, o sistema utiliza a API para verificar a existência de um save anterior. Caso exista, o jogador tem a opção de "Continuar", carregando todos os dados salvos e retomando a aventura exatamente de onde parou.

Implementação: A API foi desenvolvida utilizando as bibliotecas padrão do Python para manipulação de arquivos e o formato JSON, garantindo uma solução robusta e de fácil manutenção.

Tecnologias Utilizadas
Python 3.x

colorama (para cores no terminal)

Como Executar o Jogo
A maneira mais fácil de jogar é usando o arquivo executável pré-compilado.

Abra a pasta dist/.

Execute o arquivo main.exe.

Siga as instruções apresentadas no console para jogar.

<br>

<details>
<summary>Clique para ver a Estrutura do Projeto</summary>

em-busca-da-verdade/
├── data/
│   ├── consumables.json
│   ├── enemies.json
│   ├── items.json
│   ├── recipes_cooking.json
│   ├── recipes_craft.json
│   └── savegame.json
├── dist/
│   └── main.exe
├── main.py
├── player.py
├── menus.py
├── narrativa.py
├── savegame.py
├── utils.py
├── path_handler.py
└── requirements.txt

</details>

<details>
<summary>Clique para ver a Equipe de Desenvolvimento</summary>

Elberth Mayan

Daiane Botelho

Lais

Isaque Felix

Yasmin

</details>