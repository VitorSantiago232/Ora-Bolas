
# **Ora Bolas**

## **Visão Geral**

O "Ora Bolas" é um projeto desenvolvido para simular o movimento de um robô em direção a uma bola em um campo de futebol virtual. O projeto inclui funcionalidades para calcular trajetórias, velocidades, acelerações e distâncias, bem como para visualizar graficamente esses dados e realizar animações tanto por meio do Pygame quanto do Matplotlib.

## **Funcionalidades**

- **Calculadora de Trajetória:** Determine a trajetória do robô em direção à bola com base em suas posições no campo.
- **Gráficos Interativos:** Visualize graficamente as trajetórias, velocidades, acelerações e distâncias entre o robô e a bola.
- **Animações em Pygame:** Animações interativas que demonstram o movimento do robô em direção à bola.
- **Animações em Matplotlib:** Animações gráficas que mostram a trajetória da bola e do robô ao longo do tempo.

## **Requisitos**

- Python 3.x
- Bibliotecas:
  - `numpy`
  - `matplotlib`
  - `pygame`

## **Instruções de Uso**

1. Navegue até o diretório do projeto:

```bash
cd ora-bolas
```

2. Execute o menu de opções:

```bash
python main.py
```

3. Escolha a opção desejada e siga as instruções.

## **Exemplos de Uso**

Para calcular a trajetória do robô em direção à bola:

```python
from funcoes import trajetoria

trajetoria(x_robo, y_robo)
```

Para visualizar graficamente as velocidades em x do robô e da bola:

```python
from funcoes import velocidade_robo_bola_x

velocidade_robo_bola_x(x_robo, y_robo)
```

