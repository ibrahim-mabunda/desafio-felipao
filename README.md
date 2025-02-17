💻**Desafio do Felipão**👌

**A estrutura de decisão no código utiliza uma série de declarações if-else if para determinar o nível do herói com base na quantidade de experiência (XP). Vamos analisar cada parte:**

**Declaração if inicial:**

```
if (xp < 1000) {
    nivel = "Ferro";
}
```

**Se a quantidade de XP for menor que 1000, o nível do herói é definido como "Ferro".**

**Primeira declaração else if:**

```
if (xp < 1000) {
    nivel = "Ferro";
}
```

**Se a quantidade de XP estiver entre 1001 e 2000, o nível do herói é definido como "Bronze".**

**Segunda declaração else if:**

```
else if (xp >= 2001 && xp <= 5000) {
    nivel = "Prata";
}
```

**Se a quantidade de XP estiver entre 2001 e 5000, o nível do herói é definido como "Prata".**

**Terceira declaração else if:**

```
else if (xp >= 5001 && xp <= 7000) {
    nivel = "Ouro";
}
```

**Se a quantidade de XP estiver entre 5001 e 7000, o nível do herói é definido como "Ouro".**

**Quarta declaração else if:**

```
else if (xp >= 7001 && xp <= 8000) {
    nivel = "Platina";
}
```

**Se a quantidade de XP estiver entre 7001 e 8000, o nível do herói é definido como "Platina".**

**Quinta declaração else if:**

```
else if (xp >= 8001 && xp <= 9000) {
    nivel = "Ascendente";
}
```

**Se a quantidade de XP estiver entre 8001 e 9000, o nível do herói é definido como "Ascendente".**

**Sexta declaração else if:**

```
else if (xp >= 9001 && xp <= 10000) {
    nivel = "Imortal";
}
```

**Se a quantidade de XP estiver entre 9001 e 10000, o nível do herói é definido como "Imortal".**

**Declaração else final:**

```
else if (xp >= 10001)
```
