# PPO-PyTorch

Implementación mínima de PyTorch de PPO con objetivo recortado para entornos de gimnasios OpenAI.

## ℹ️ Instrucciones

- Si deseas probar la red preentrenada : ejecuta `test.py` o `test_continuous.py`
- Para entrenar de nuevo : ejecuta `PPO.py` o `PPO_continuous.py`
- Todos los hiperparámetros estan en los archivos `PPO.py` o `PPO_continuous.py`
- Si está intentando entrenarlo en un entorno donde la dimensión de la acción = 1, asegúrese de verificar las dimensiones del tensor en la función de actualización de la clase PPO, ya que he usado `torch.squeeze ()` varias veces. `torch.squeeze ()` aprieta el tensor de manera que no haya dimensiones de longitud = 1 ([mayor información](https://pytorch.org/docs/stable/torch.html?highlight=torch%20squeeze#torch.squeeze)).
- Número de actores para recopilar experiencia = 1. Esto podría cambiarse creando múltiples instancias de redes ActorCritic en la clase PPO y usándolas para recopilar experiencia (como A3C y PPO estándar)


## 📚 Referencias

- PPO [paper](https://arxiv.org/abs/1707.06347)
- [OpenAI Spinning up](https://spinningup.openai.com/en/latest/)
