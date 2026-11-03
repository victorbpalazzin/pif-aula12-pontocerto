# Respostas da dupla — Atividade PontoCerto

## Dupla

| Papel | Nome completo | Usuário do GitHub |
|---|---|---|
| Integrante 1 (dono do fork) | Victor Bacelar | victorbpalazzin |
| Integrante 2 (colaborador) | Luiza Beltrão | A confirmar pela integrante |

## Explicação da solução

<!-- 3 a 5 linhas: como calculaPontos e as fábricas de campanhas eliminam a repetição de código? -->

## Desafio 2

<!-- Por que, nas duas promoções de um dia, faz sentido usar lambda em vez de função nomeada? -->

As regras são curtas e usadas somente nessas promoções. A lambda permite passar
a conta diretamente para `calculaPontos`, sem criar um nome para cada promoção
temporária. O primeiro argumento de `calculaPontos` tem tipo `Int -> Int`:
é uma função que recebe os pontos base e devolve os pontos finais.

## Desafio 3

<!-- O que campanhaMultiplicadora 5 devolve? Um número ou outra coisa? Como o :t confirma isso? -->

Devolve uma função que multiplica os pontos por 5, e não um número.
Ela ainda precisa receber os pontos. No GHCi, `:t campanhaMultiplicadora 5`
mostraria `campanhaMultiplicadora 5 :: Int -> Int`, confirmando que o resultado
é uma função. `blackFriday` guarda essa regra e também tem tipo `Int -> Int`.
Usamos o Playground, que não oferece `:t`; conferimos as assinaturas no código
e executamos as regras com o compilador GHC.

## Desafio 4

**a)** <!-- Por que as duas ordens dão resultados diferentes? -->

**b)** <!-- Qual ordem garante que o bônus de aniversário não seja multiplicado? Por quê? -->

## Desafio 5 — revisão de código

| Erro | Função | O que estava errado | Como o GHC avisou (resumo da mensagem) | Como corrigimos |
|---|---|---|---|---|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |
| 4 | | | | |

## Desafio 6 — Haskell × C

<!-- Cite duas diferenças entre o calculaPontos em Haskell e o calculaPontos em C. -->

## Evidência de execução

Saída do `main` de `fidelidade.hs`:

```text
(cole aqui)
```

Saída do `main` de `revisao.hs` (depois de corrigido):

```text
(cole aqui)
```

Saída de `pontocerto.c`:

```text
(cole aqui)
```
