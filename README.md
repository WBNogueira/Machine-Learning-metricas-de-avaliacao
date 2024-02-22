# Cálculo de Métricas de Avaliação de Aprendizado

Este repositório contém código Python para treinar e avaliar modelos de redes neurais convolucionais (CNNs) usando TensorFlow e Keras. O objetivo principal é classificar dígitos escritos à mão usando o conjunto de dados MNIST.
Descrição do Código
-------------------

O código inclui as seguintes etapas:

1. **Importação de Bibliotecas e Carregamento de Dados**: Importação das bibliotecas necessárias, carregamento dos dados do conjunto de dados MNIST e pré-processamento das imagens.

2. **Definição e Treinamento do Modelo**: Definição da arquitetura do modelo CNN usando a API Sequencial do Keras, compilação do modelo com otimizador 'adam' e função de perda 'sparse_categorical_crossentropy', e treinamento do modelo com os dados de treinamento.

3. **Avaliação do Modelo e Matriz de Confusão**: Avaliação do modelo treinado usando os dados de teste e geração de uma matriz de confusão para avaliar o desempenho do modelo.

4. **TensorBoard**: Utilização do TensorBoard para visualização e monitoramento do treinamento, incluindo métricas como acurácia, sensibilidade, F1 Score e área sob a curva (AUC).

Como Usar
---------

Para utilizar este código, siga estas etapas:

1. Clone o repositório para o seu ambiente local.
2. Execute o código Python em um ambiente compatível com TensorFlow e Keras.
3. Analise os resultados do treinamento, incluindo métricas de desempenho, usando o TensorBoard.

Requisitos
----------

* Python
* TensorFlow
* Keras
* Matplotlib
* Seaborn
* Pandas

Contribuições
-------------

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou enviar solicitações de pull com melhorias ou correções.

## Agradecimentos

Este projeto foi feito para estudo junto com a DIO.me, o python foi utilizado o Coleb e dúvidas foram tiradas do ChatGPT (IA).

## Autor

Wagner Nogueira


