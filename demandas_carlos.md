## Demandas

1 - Escolher a região de simulação.
2 - Salvar a posição da antena escolhida. (Se possivel justificar a escolha).
3 - Colocar no minimo dois receptores na cena em posições reais.
4 - Usar o scene.preview() para ver a posição no mapa e encontra-los.
5 - Calcular os caminhos dos raios usando o codigo abaixos

```
paths = scene.compute_paths(diffraction=True,
                                max_depth=3)
```

6 - Renderizar os caminhos com um novo scene.preview()
