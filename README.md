# Perguntas a serem respondidas

## 1. Por que é necessário calcular a derivada parcial?

calculamos a derivada parcial para saber como cada peso da rede neural afeta o erro. Assim, conseguimos ajustar os pesos na direção certa para que a rede erre menos.

## 2. Por que usar uma função sigmoid? Por que a função ReLU é mais usada?

A função sigmoid é usada porque ela deixa tudo entre 0 e 1, o que ajuda em alguns tipos de problemas. Mas hoje em dia a ReLU é mais usada porque ela é mais rápida e funciona melhor em redes grandes, já que evita alguns problemas que a sigmoid tem, como o gradiente ficar muito pequeno.
