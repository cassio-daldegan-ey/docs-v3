.. doc-hvdc documentation master file, created by
   sphinx-quickstart on Fri Feb  7 13:35:16 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Documentação - HVDC Termografia
===============================

Essa documentação está separada em cinco categorias:

* **Introdução**: Visão geral sobre o projeto, compreendendo seus princiapis objetivos.

* **load_data**: Script de extração dos dados utilizados no modelo (dados de câmeras termográficas e dados do SAGE).

* **process_data**: Script de tratamento dos dados para servirem de insumo dos modelos de previsao e para gerar as estatísticas descritivas utilizadas no dashboard.

* **build_features**: Script de seleção de variáveis utilizadas como explicativas no modelo preditivo.

* **train_model**: Script de treinamento e previsão dos modelos de série temporal.

* **evaluate_model**: Script de cálculo do MAPE por modelo preditivo.

* **predict_model**: Script de rotina de previsão de temperatura.

* **visualize**: Script de tratamento das bases de dados para serem utilizadas no dashboard.

* **Dashboard**: Explicacão sobre os visuais do dashboard.

.. toctree::
   :maxdepth: 2
   :caption: Conteúdo:
   
   introducao
   load_data
   process_data
   build_features
   train_model
   evaluate_model
   predict_model
   visualize
   dash