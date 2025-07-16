# Forensic Age Prediction using Convolutional Neural Networks (CNNs)

Este repositório contém código e notebooks para a análise de redes neurais convolucionais (CNNs) aplicadas à classificação etária forense utilizando radiografias panorâmicas odontológicas. O objetivo deste trabalho é investigar o desempenho de diferentes arquiteturas de CNNs, juntamente com técnicas de pré-processamento de imagens, para estimar a faixa etária de indivíduos com base em exames odontológicos.

## Estrutura do Repositório

- `Training_Evaluation_CNNs_Age_Classification.ipynb`: Notebook que contém o processo de treinamento e avaliação das arquiteturas CNN (VGG19, InceptionV3, EfficientNetV2B0) para classificação etária.
  
- `Average_Accuracy_Filters_Models_Standard_Deviation.ipynb`: Código para gerar gráficos comparando a acurácia média entre os modelos e filtros utilizados, incluindo o desvio-padrão.
  
- `Visualization_Learning_Curves.ipynb`: Gerador de curvas de aprendizado (acurácia e perda) para as diferentes arquiteturas e filtros aplicados durante o treinamento.
  
- `README.md`: Este arquivo que fornece a descrição do repositório e orientações gerais.

## Funcionalidades

1. **Pré-processamento de Imagens**: Técnicas de realce de imagem, como Laplaciano, Sobel, Prewitt, Top-Hat, Black-Hat, entre outras, são aplicadas para melhorar a qualidade das radiografias, otimizando a entrada das CNNs.

2. **Treinamento de Modelos**: Três arquiteturas de redes neurais convolucionais pré-treinadas (VGG19, InceptionV3, EfficientNetV2B0) são ajustadas para a tarefa de classificação etária.

3. **Avaliação de Modelos**: O desempenho dos modelos é avaliado utilizando métricas como acurácia, precisão, recall e F1-score. A validação cruzada estratificada é aplicada para garantir a robustez dos resultados.

4. **Visualização dos Resultados**: Gráficos de barras e curvas de aprendizado são gerados para comparar o desempenho dos modelos e analisar a acurácia e a perda durante o treinamento.

## Como Usar

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/seu-usuario/Forensic_Age_Prediction_CNNs.git

2.Instale as Dependências:
Certifique-se de ter o Python 3.x instalado e as bibliotecas necessárias. Você pode instalar as dependências com o seguinte comando:

bash
Copiar
Editar
pip install -r requirements.txt

3. Execute os Notebooks:
Abra e execute os notebooks conforme sua necessidade, certificando-se de que as imagens e os rótulos estejam corretamente carregados no diretório dataset/.


Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias. Fique à vontade para adicionar mais testes, documentação ou otimizações.



### O que foi adicionado:

- Descrição geral do projeto
- Estrutura do repositório
- Funcionalidades principais
- Como rodar o código (clone e instalação de dependências)
- Como contribuir para o repositório
- Informações de licença (caso você tenha um arquivo de licença no repositório)

Esse README fornece uma visão clara do seu projeto, facilitando a compreensão e o uso do código para outros desenvolvedores.
