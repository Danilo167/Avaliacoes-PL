# Tabuada Centenar - Clojure

Programa que gera a tabuada de um número com um sinal matemático escolhido pelo usuário, calculando o resultado entre o número informado e todos os valores de 0 a 99.

## Como usar

```clojure
(tabuada numero sinal)
```

**Exemplo:**
```clojure
(tabuada 4 +)
; => 4 + 0 = 4
; => 4 + 1 = 5
; => ...
; => 4 + 99 = 103
```

## Sinais suportados

| Sinal | Operação      |
|-------|---------------|
| `+`   | Adição        |
| `-`   | Subtração     |
| `*`   | Multiplicação |
| `/`   | Divisão       |
