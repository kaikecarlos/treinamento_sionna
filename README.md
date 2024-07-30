## Demandas

- [x] Escolher a região de simulação. (-38.51023,-3.72479,-38.50522,-3.72078)
- [ ] Salvar a posição da antena escolhida. (Se possivel justificar a escolha).
- [ ] Colocar no minimo dois receptores na cena em posições reais.
- [ ] Usar o scene.preview() para ver a posição no mapa e encontra-los.
- [ ] Calcular os caminhos dos raios usando o codigo abaixos

```
paths = scene.compute_paths(diffraction=True,
                                max_depth=3)
```

- [ ] Renderizar os caminhos com um novo scene.preview()
