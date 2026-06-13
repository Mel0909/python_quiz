# 🐍 Python Quiz — Elas pelas Exatas

Ferramenta de dinâmica interativa para aulas de Python básico, desenvolvida para o curso de programação do **[Elas pelas Exatas](https://elaspelasexatas.com.br)**.

---

## Sobre

O **Python Quiz** é um site estático usado durante as aulas como atividade em grupo. A dinâmica é simples: um trecho de código Python aparece na tela e as alunas tentam descobrir o que ele faz e qual será a saída no terminal — antes de clicar em revelar o gabarito.

O objetivo é desenvolver a habilidade de **leitura de código** e o raciocínio lógico de forma leve e colaborativa, sem precisar de nenhuma instalação ou cadastro.

---

## Conteúdo

O quiz cobre os 9 capítulos da apostila do curso, com 3 exercícios por tópico (27 no total):

| # | Tópico | Conceitos |
|---|--------|-----------|
| 01 | Introdução ao Python | `print()`, `type()`, strings vs números |
| 02 | Variáveis | Tipos de dados, atribuição, concatenação |
| 03 | Operações Aritméticas | `+` `-` `*` `/` `//` `%` `**` |
| 04 | Operações Lógicas | `and`, `or`, `not`, operadores relacionais |
| 05 | Condicionais | `if`, `elif`, `else` |
| 06 | Listas | Índices, `append()`, `remove()`, `sort()` |
| 07 | Estruturas de Repetição | `for`, `while`, `range()` |
| 08 | Funções | `def`, parâmetros, `return` |
| 09 | Bibliotecas | `math`, `random` |

---

## Como usar em aula

1. Abra o `python_quiz.html` no navegador (ou acesse pelo link do GitHub Pages)
2. Selecione o tópico da aula
3. Projete o código na tela para a turma
4. Dê um tempo para as alunas discutirem e anotarem o que acham que acontece
5. Clique em **Ver Gabarito** para revelar a resposta com animação de terminal
6. Use os botões de navegação para avançar entre os exercícios

---

## Estrutura do projeto

```
python-quiz/
├── python_quiz.html   # Estrutura e lógica (HTML + JavaScript)
├── style.css          # Estilo visual (tema rosa e preto)
└── README.md
```

---

## Deploy

O site é estático — sem dependências, sem build, sem npm.

**GitHub Pages:**
1. Vá em **Settings → Pages**
2. Em *Source*, selecione **"Deploy from a branch"**
3. Escolha a branch `main` e a pasta `/ (root)`
4. O site ficará disponível em `seuusuario.github.io/nome-do-repo`

---

## Tecnologias

- HTML5 + CSS3 + JavaScript puro — sem frameworks
- Fontes: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [DM Sans](https://fonts.google.com/specimen/DM+Sans), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts
- Highlight de sintaxe Python feito com tokenizador próprio (sem bibliotecas externas)

---

## Sobre o Elas pelas Exatas

O [Elas pelas Exatas](https://elaspelasexatas.com.br) é um programa da USP que oferece cursos gratuitos de exatas para mulheres, com o objetivo de reduzir a desigualdade de gênero nas áreas de ciência e tecnologia.

---

*Feito com carinho para as alunas do curso de Python* 🩷
