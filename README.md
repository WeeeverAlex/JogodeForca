# JogodeForca

Esse é um projeto da matéria de Algebra Linear e Teoria da Informação do Insper para o curso de Ciência da Computação.

# Projeto: Jogo de Forca

Neste projeto, usaremos o conceito de entropia e tudo o que analisamos até o momento para fazer um jogador de forca. objetivo da atividade é fazer um jogador automático de forca que ganha o máximo de vezes possível com apenas 5 vidas. Ao criar um novo jogo, o jogador recebe a informação de quantas letras a palavra tem. Em uma jogada típica, o jogador escolhe uma letra. O "juiz" retorna ua lista com os índices em que essa letra aparece na palavra secreta. Se a letra não aparece, retorna uma lista vazia e o jogador perde uma vida. A qualquer momento, o jogador pode consultar suas vidas (`jogo.vidas`), mas, obviamente, não pode consultar a palavra escolhida. O jogador ganha quando, por saber qual palavra foi escolhida, usa o método `tentar_palavra` informando a palavra correta. Se usar o método mas não acertar, perde o jogo imediatamente. Sempre que o jogador ganha o juiz retorna `True`. Quando ele perde, retorna `False`.

## Modelo matemático e Explicação


## Resultado final


## Como rodar o projeto e funcionalidades

### Clone o repositório do nosso projeto:

```py
https://github.com/WeeeverAlex/JogodeForca
```

### Depois instale os requirements:

```py
pip install -r requirements.txt
```

## Por fim, basta executar o arquivo notebook.ipynb: 

```py
python demo.ipynb
```

## Autores

- [@st4pzz](https://github.com/st4pzz)
- [@WeeeverAlex](https://github.com/WeeeverAlex)

## Fonte Bibliográfica

IME USP. br-sem-acentos. Disponível em <https://www.ime.usp.br/~pf/dicios/br-sem-acentos.txt>. Acesso em 09 de Maio de 2023.


