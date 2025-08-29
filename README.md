# Matriz_de_confusao

# Projeto de classificação de dígitos manuscritos (MNIST) usando CNNs em TensorFlow/Keras via Google Colab.

Inclui:

# Treinamento de CNN para classificar dígitos (0–9).

- Geração da matriz de confusão.

- Cálculo de métricas por classe: Sensibilidade, Especificidade, Acurácia, Precisão e F1-score.

- Visualização com TensorBoard direto no Colab.

# Versão do python:
- Python 3.12.11

# Correções do código original:
- y_pred=model.predict_classes(test_images) # forma não utilizada obsoleto ".predict_classes()"

- y_pred=model.predict(test_images) #nova forma "predict()"
# Métricas Calculadas

- Por classe (0–9):

- VP, VN, FP, FN

- Sensibilidade (Recall)

- Especificidade

- Acurácia

- Precisão (Precision)

- F-score
