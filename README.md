# JogodeForca

Esse é um projeto da matéria de Algebra Linear e Teoria da Informação do Insper para o curso de Ciência da Computação.

# Projeto: Jogo de Forca

Neste projeto, o grupo deverá projetar e avaliar um jogador de forca. Em sua avaliação, deve executar um número grande de jogos diferentes (no mínimo 100) e então reportar a probabilidade de seu algoritmo vencer o jogo.

## Explicação

A ideia do nosso algoritmo é que ele implemente uma estratégia para jogar um jogo de forca, no qual, o jogo fornece um conjunto de palavras e escolhe uma aleatoriamente. O objetivo do algoritmo é adivinhar a palavra escolhida pelo jogo, seja tentando letras ou palavras diretamente, e isso tudo antes que as vidas acabem, já que oo número de vidas é reduzido quando uma tentativa errada é feita.
A estratégia do nosso algoritmo é a seguinte: 

Começamos filtrando as palavras do conjunto de palavras fornecido pelo jogo para aquelas que têm o mesmo tamanho da palavra escolhida pelo jogo. Em seguida, é construído um dicionário das letras que aparecem nas palavras filtradas e suas frequências. As letras são então ordenadas em ordem decrescente de frequência. É feito um loop, tentando adivinhar a palavra escolhida pelo jogo. A estratégia principal do algoritmo dentro deste loop é sempre tentar a letra com a maior frequência entre as palavras filtradas. Se a tentativa de adivinhar uma letra for bem-sucedida, são filtradas as palavras para aquelas que têm a letra nos mesmos índices que na palavra do jogo. Se a tentativa falhar, o algoritmo filtra as palavras para aquelas que não contêm a letra. O dicionário de letras e suas frequências são atualizados com base nas palavras filtradas restantes. O loop continua até que o algoritmo adivinhe a palavra ou até que não haja mais vidas. Se restar apenas uma palavra, o algoritmo tentará adivinhá-la. Se houver várias palavras e apenas uma vida, ele escolherá aleatoriamente uma das palavras para adivinhar. Assim, nosso algoritmo utiliza uma estratégia estatística, tentando sempre a letra mais frequente nas palavras possíveis restantes, para adivinhar a palavra do jogo.

## Resultado Final

![image](https://github.com/WeeeverAlex/JogodeForca/assets/89090868/c2176fc2-820a-443c-963e-035185e54d10)

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

TIAGO FERNANDES TAVARES. 07-compressao.ipynb. Disponível em <https://github.com/tiagoft/alglin-alunos/blob/main/07-compressao.ipynb>. Acesso em 09 de Maio de 2023.
