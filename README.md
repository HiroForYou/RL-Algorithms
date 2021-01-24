<h2 align="center">
<p>Aprendizaje Reforzado</p>
</h2>

<h2 align="center">
<p></p>
<img src="https://img.shields.io/badge/PyTorch%20-%23EE4C2C.svg?&style=for-the-badge&logo=PyTorch&logoColor=white" />
<img src="https://img.shields.io/badge/numpy%20-%23013243.svg?&style=for-the-badge&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter" />
<p></p>
</h2>

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HiroForYou/RL-Algorithms/blob/master/main.ipynb)



## 🆕 Update
- 23/01/21: Modelos agregados: PPO y World Models, se actualizaron las dependencias de las paqueterías de tal forma que no genere conflictos a la hora de ejecutarlos desde Colab. Puedes usar los siguientes entornos con GYM: LunarLander-v2, CarRacing y BipedalWalker-v3.

## ℹ️ Instrucciones
Si desea ver con más detalle la explicación teórica, consulte `main.ipynb`

A continuación se muestran los resultados para el algoritmo PPO:

PPO Discretizado LunarLander-v2 (1200 episodios)           |  PPO Contínuo BipedalWalker-v3 (4000 episodios)
:-------------------------:|:-------------------------:
![](PPO-PyTorch/gif/PPO_LunarLander-v2.gif) |  ![](PPO-PyTorch/gif/PPO_BipedalWalker-v2.gif)


También mostramos como se vería la salida del enfoque World Models en el circuito de coches:
<p align="center">
  <img src="World-Models-PyTorch/src/car.gif" />
  <p align="center">"Reconstuyendo los sueños"</p>
</p>

## 👨‍💻 Maintainers
* Cristhian Wiki, Github: [HiroForYou](https://github.com/HiroForYou) Email: csanchezs@uni.pe

## 🙏🏽 Agradecimientos
* Version 0.1:
Este repositorio se baso principalmente en estos artículos de [towardsdatascience](https://towardsdatascience.com/introduction-to-proximal-policy-optimization-tutorial-with-openai-gym-environment-d1d80036e7c2) y [medium](https://medium.com/arxiv-bytes/summary-world-models-b050be1bf2d5) para el enfoque teórico, le recomiendo encarecidamente invierta su tiempo en dichas lecturas, son una buena apuesta!
En cuanto al código, me base en los siguientes repositorios de [pytorch-vae](https://github.com/sksq96/pytorch-vae.git) y [PPO-PyTorch](https://github.com/nikhilbarhate99/PPO-PyTorch.git). Yo solo hice algunas modificaciones a sus implementaciones por cuestiones de incompatibilidades de Pyglet, Gym y Box2D, de tal forma que puedan ejecutarse sin problemas desde Google Colab. 

* Version 0.2:
*Soon*