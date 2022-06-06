# Jogos - Python

O código deste repositório foi desenvolvido durante as aulas do curso de Python 3 da Alura.

Para rodar o projeto, é necessário ter Python 3 instalado e é possível iniciar a versão com menu de escolha de jogos partir do arquivo [`jogos.py`](./jogos.py) ou iniciar diretamente cada um dos jogos [`adivinhacao.py`](./adivinhacao.py) ou [`forca.py`](./forca.py)

O comando para rodar a partir do menu é:
`python jogos.py` ou `python3 jogos.py` caso exista mais de uma versão de Python instalada

Para rodar os jogos o comando é semelhante:
- `python adivinhacao.py` ou `python3 adivinhacao.py`
- `python forca.py` ou `python3 forca.py`

- O jogo de adivinhação irá escolher um número com a bibioteca `random` e, de acordo com o nível selecionado, permitirá mais tentativas ou menos tentativas para adivinhar o número escolhido para aquela rodada.

- O jogo da forca lê uma [lista de palavras](./palavras.txt) e o jogador tem o objetivo de adivinhar todas as letras da palavra escolhida antes que o número máximo de tentativas para aquela rodada termine.
    - A cada nova rodada será sorteada uma nova palavra da lista.