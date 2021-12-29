# Trilha de Estudos de Ciência de Dados

Este é um repositório em constante construção e atualização. Adiciono aqui técnicas de estudo e fontes que considero boas para o aprendizado de ciência de dados, com o objetivo de manter recursos organizados para consulta e ajudar quem se interessa pelo tema. O conteúdo aqui compilado vai do básico ao avançado.

# Sumário
- [Como estudar](https://github.com/HinePo/Trilha-de-Estudos-de-Data-Science/blob/main/README.md#como-estudar)
- [Ferramentas](https://github.com/HinePo/Trilha-de-Estudos-de-Data-Science/blob/main/README.md#ferramentas)
- [Python and Data Analysis basics](https://github.com/HinePo/Trilha-de-Estudos-de-Data-Science/blob/main/README.md#python-and-data-analysis-basics)
- [Data Visualization](https://github.com/HinePo/Trilha-de-Estudos-de-Data-Science/blob/main/README.md#data-visualization)
- [Machine Learning - Teoria](https://github.com/HinePo/Trilha-de-Estudos-de-Data-Science/blob/main/README.md#machine-learning---teoria)
- [Machine Learning - Prática](https://github.com/HinePo/Trilha-de-Estudos-de-Data-Science/blob/main/README.md#machine-learning---prática)
- [Deep Learning - Neural Networks](https://github.com/HinePo/Trilha-de-Estudos-de-Data-Science/blob/main/README.md#deep-learning---neural-networks)
- [Transformers](https://github.com/HinePo/Trilha-de-Estudos-de-Data-Science/blob/main/README.md#transformers)
- [NLP - Natural Language Processing](https://github.com/HinePo/Trilha-de-Estudos-de-Data-Science/blob/main/README.md#nlp---natural-language-processing)
- [Computer Vision](https://github.com/HinePo/Trilha-de-Estudos-de-Data-Science/blob/main/README.md#computer-vision)
- [MLOps](https://github.com/HinePo/Trilha-de-Estudos-de-Data-Science/blob/main/README.md#mlops)
- [Youtube channels](https://github.com/HinePo/Trilha-de-Estudos-de-Data-Science/blob/main/README.md#youtube-channels)
- [Perfis no Instagram](https://github.com/HinePo/Trilha-de-Estudos-de-Data-Science/blob/main/README.md#perfis-no-instagram)

# Como estudar
- Criar um doc (word) pessoal com a sua organização do que vc já aprendeu/estudou e o que planeja aprender/estudar, de preferência organizado por mês ou bimestre. Procurar manter este doc atualizado, se possível;
- Instalar a extensão [video speed controller](https://chrome.google.com/webstore/detail/video-speed-controller/nffaoalbilbmmfgbnbgppjihopabppdk) no google chrome (funciona em qualquer vídeo tocado pelo chrome browser), e aprender a usar:

![image](https://user-images.githubusercontent.com/66163270/145697555-17f7fb51-ec8d-4f9f-8c36-654b062cddce.png)

Isso aumentará muito a sua produtividade.
-	Ao entrar em um assunto novo, gosto de ver um ou dois vídeos de ~10 min no youtube, pesquisar sobre o tema focando em material escrito, e estudar aplicações;
-	Evitar ficar muito tempo na parte teórica: Qualquer assunto novo tem suas aplicações, via bibliotecas específicas. Se familiarizar com a documentação é o primeiro passo (google “pandas docs”, “seaborn cheat sheet”...);
-	O segundo passo é a aplicação e uso, parte prática: Resolver problemas usando IA: Pesquisar aplicações no Kaggle (notebooks), fazer o fork (Copy and Edit), adicionar ideias. Evitar tentar reinventar a roda: aproveitar os códigos que já existem;
- Adicionar aplicação ao seu repositório pessoal (público ou privado) de forma organizada para que você possa facilmente consultá-la no futuro.

# Ferramentas
- Focar em Google Colab e Kaggle notebooks.
- No futuro, é interessante conhecer IDEs como VS Code, PyCharm e Spyder.
- Sublime Text é um ótimo editor de código.

# Python and Data Analysis basics
- [Never memorize code](https://www.youtube.com/watch?app=desktop&v=AavXBoxTCIA) - vídeo
- [How to learn data science smartly](https://www.youtube.com/watch?app=desktop&v=csG_qfOTvxw) - vídeo
- [Didática Tech playlists](https://www.youtube.com/c/Did%C3%A1ticaTech/playlists?app=desktop)
- [Curso em vídeo playlists](https://www.youtube.com/c/CursoemV%C3%ADdeo/playlists?app=desktop)
- [Reuven youtube channel](https://www.youtube.com/reuvenlerner)
- [Python projects](https://medium.com/coders-camp/180-data-science-and-machine-learning-projects-with-python-6191bc7b9db9)
- [Learn Pandas with pokemons](https://www.kaggle.com/ash316/learn-pandas-with-pokemons)
- [Pandas docs](https://pandas.pydata.org/docs/index.html)

### Data Analysis workflow - entender e praticar as etapas básicas:

- Importar e ler csv, criar dataframe
- Checar tipos de variáveis (data types): numéricas e categóricas
- Preproces: Técnicas para lidar com variáveis categóricas: one-hot encoding, label encoding, ordinal encoding....
- Plots básicos
- Analisar missing values (valores faltantes), tomar decisões sobre o que fazer com eles
- Analisar outliers, decidir o que fazer com eles
- Análise univariada, bivariada, multivariada
- Feature Engineering (criação de variáveis)
- Deixar dados prontos para eventual modelagem de IA

### Machine Learning workflow - entender e praticar as etapas básicas:

- Split train/validation datasets
- Definir Features and Target (if it is a supervised problem)
- Preprocess: Scaling and categorical encoders
- Definir métricas de avaliação dos modelos
- Choose algorithm, Train model
- Evaluate model
- Melhorar modelo, tunar hiperparâmetros, treinar de novo, avaliar de novo
- Ensemble: combinar modelos para aumentar performance e poder de generalização

# Data Visualization
- [A Simple Tutorial To Data Visualization](https://www.kaggle.com/vanshjatana/a-simple-tutorial-to-data-visualization#notebook-container) - @vanshjatana
- [Séries de notebooks de visualização](https://www.kaggle.com/residentmario/univariate-plotting-with-pandas) - ao final de cada notebook tem um link para o próximo
- [Data Analysis - Brazilian Society (PNAD)](https://www.kaggle.com/hinepo/pnad-data-analysis) - @hinepo
- [Rio Temperature Analysis](https://www.kaggle.com/hinepo/is-rio-getting-hotter-seasons-analysis/) - @hinepo
- [Power BI playlists](https://www.youtube.com/c/HashtagTreinamentos/playlists?app=desktop)
- [Power BI - Karine Lago](https://www.youtube.com/c/KarineLago/playlists?app=desktop)
- [Power BI + DAX + Projetos na prática - Curso Udemy](https://www.udemy.com/course/curso-de-powerbi-desktop-dax/)

# Machine Learning - Teoria
- [Supervised x Unsupervised Learning](https://www.youtube.com/watch?app=desktop&v=1FZ0A1QCMWc) - vídeo
- [Supervised x Unsupervised Learning: applications](https://www.youtube.com/watch?app=desktop&v=rHeaoaiBM6Y) - vídeo
- Pesquisar sobre Overfitting e Underfitting, ver vídeos e gráficos
- [Cross Validation](https://www.youtube.com/watch?app=desktop&v=fSytzGwwBVw)
- [Cross Validation - scikit docs](https://scikit-learn.org/stable/modules/cross_validation.html)
- Pesquisar sobre Cross Validation para Time Series (como evitar contaminação de dados do futuro pro passado, data leakage, train/test contamination...)
- [pdf do livro do Abhishek Thakur](https://github.com/abhishekkrthakur/approachingalmost/blob/master/AAAMLP.pdf) - resumo com tudo, disponível na Amazon tb
- [Kaggle courses](https://www.kaggle.com/learn)
- [Statquest - Vídeos sobre conceitos, teoria e matemática de algoritmos e ML](https://www.youtube.com/c/joshstarmer/playlists?app=desktop)
- [Scikit-learn](https://scikit-learn.org/stable/)
- [Scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html) - Acho muito importante ler todo o item 1. Na primeira leitura não precisa entender tudo com profundidade, mas tem que se familiarizar com a documentação do scikit, especialmente com o item 1 todo. É uma biblioteca muito importante para se aprender a usar e consultar.
- [Scikit-learn Pre-processing](https://scikit-learn.org/stable/modules/preprocessing.html)
- [ML projects for beginners - with code](https://github.com/microsoft/ML-For-Beginners)
- [Scipy docs](https://scipy.org/) - Procurar aplicação do pacote
- Pesquisar sobre "Feature Engineering" (criação de variáveis)
- Pesquisar sobre métricas e como avaliar modelos:
  - Classificação: Accuracy, ROC AUC, f1-score, recall, precision
  - Regressão: RMSE, MSE, MAE, R²
- Outros conceitos importantes: Pesquisar sobre Boosting (XGBoost, LGBM, GBM), Bagging, Split train/test, data leakage, time series, ARIMA, feature importances, ensemble...
- Imbalanced learning:
  - downsampling/upsampling
  - [Transforming skewed data](https://medium.com/@ODSC/transforming-skewed-data-for-machine-learning-90e6cc364b0) - como tratar o viés no dados
  - [imblearn](https://opendatascience.com/strategies-for-addressing-class-imbalance/)
  - [Oversampling x Undersampling](https://www.kdnuggets.com/2020/01/5-most-useful-techniques-handle-imbalanced-datasets.html)
  - [Resampling example](https://www.kaggle.com/rafjaa/resampling-strategies-for-imbalanced-datasets)
  - [SMOTE for classification example](https://www.kaggle.com/shrutimechlearn/pokemon-classification-and-smote-for-imbalance/notebook)

# Machine Learning - Prática
- [Kaggle's 30 Days of ML](https://www.youtube.com/playlist?app=desktop&list=PL98nY_tJQXZnP-k3qCDd1hljVSciDV9_N) - Abhishek Thakur
- [Applied Machine Learning](https://www.kaggle.com/vanshjatana/applied-machine-learning) - @vanshjatana
- [Data Visualization & Income Prediction for Brazilians](https://www.kaggle.com/hinepo/pnad-income-prediction) - @hinepo
- [Lazy Predict](https://www.kaggle.com/hinepo/pnad-lazy-predict) - @hinepo
- [Heart disease and ensembling](https://www.kaggle.com/hinepo/ensemble-to-predict-diabetes-100-acc-on-val-data) - @hinepo
- Browse kaggle, ver notebooks e datasets dos assuntos que te interessam
- Fazer forks de notebooks do kaggle (Copy and Edit), testar hipóteses e técnicas
- Falar com as pessoas do kaggle, comentar e postar, fazer parte da comunidade
- Competições 'Getting Started': estudar notebooks com bom score, e usar técnicas e conceitos aprendidos para criar o seu próprio. Estudar notebooks com score médio, comparar com os de score bom, e entender o que causou a melhora na pontuação. Recomendo no mínimo uns 10 dias de estudo para cada uma das competições abaixo:
  - [Titanic Classification](https://www.kaggle.com/c/titanic)
  - [House Prices Regression](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
  - [Predict Future Sales](https://www.kaggle.com/c/competitive-data-science-predict-future-sales)
  - [Tabular Playground Series](https://www.kaggle.com/c/tabular-playground-series-sep-2021)
  - Nível avançado: competições reais (valendo prêmios)


### Algorithm Optimization & Tuning techniques

- [Optuna library](https://optuna.org/)
- [Optuna example - notebook](https://www.kaggle.com/hinepo/extra-trees-optimization-with-optuna) - @hinepo
- [Optuna example](https://www.youtube.com/watch?v=m5YSKPMjkrk&list=PL98nY_tJQXZnP-k3qCDd1hljVSciDV9_N&index=23) - Abhishek Thakur
- [Optuna official tutorial](https://optuna.readthedocs.io/en/stable/tutorial/index.html)
- [Tuning techniques](https://www.youtube.com/watch?v=5nYqK-HaoKY) - Abhishek Thakur

# Deep Learning - Neural Networks
Principais conceitos e keywords a pesquisar e aprender: tensors, gradient descent, automatic differentiation, forward pass, backpropagation, layers, vanishing gradients, exploding gradients, transfer learning (fine-tuning & feature extraction)...

- [Fine-tuning x Feature Extraction - pytorch docs and examples](https://pytorch.org/tutorials/beginner/finetuning_torchvision_models_tutorial.html)

"In finetuning, we start with a pretrained model and update all of the model’s parameters for our new task, in essence retraining the whole model. In feature extraction, we start with a pretrained model and only update the final layer weights from which we derive predictions."

- [Aula Intro de DL - Lex Friedman](https://www.youtube.com/watch?app=desktop&v=O5xeyoRL95U) - vídeo
- [Pytorch vs Tensorflow in 2022](https://www.assemblyai.com/blog/pytorch-vs-tensorflow-in-2022/) - tendências
- [Keras docs](https://keras.io/)
- [Keras Sequential class](https://keras.io/api/models/sequential/)
- [Keras - code examples](https://keras.io/examples/)
- [Tensorflow docs](https://www.tensorflow.org/)
- [Pytorch docs - getting started](https://pytorch.org/get-started/locally/)
- [Pytorch - Abhishek Thakur playlist and tutorials](https://www.youtube.com/playlist?app=desktop&list=PL98nY_tJQXZln8spB5uTZdKN08mYGkOf2)
- [Pytorch - torch.nn](https://pytorch.org/docs/stable/nn.html)

Um estudo muito útil e proveitoso é comparar e olhar em paralelo as documentações de Quick Start do Keras, do Tensorflow e do Pytorch. A lógica é bem parecida e existem muitas analogias:
- [Keras Quick Start](https://www.tensorflow.org/tutorials/quickstart/beginner)
- [Tensorflow Quick Start](https://www.tensorflow.org/tutorials/quickstart/advanced)
- [Pytorch Quick Start](https://pytorch.org/tutorials/beginner/basics/data_tutorial.html)

Principais tipos de camadas (layers):
- Dense & Linear (fully connected)
- Activation functions (ReLU, LeakyReLU, SELU, PReLU, Tanh, Softmax....)
- Conv (Convolutional)
- Flatten
- Batch Normalization
- LSTM (Long Short Term Memory)
- GRU (Gated Recurrent Unit - Short Term Memory)
- Dropout
- Pooling

### Extra:

- [JAX docs](https://jax.readthedocs.io/en/latest/) 

"JAX is Autograd and XLA, brought together for high-performance numerical computing and machine learning research. It provides composable transformations of Python+NumPy programs: differentiate, vectorize, parallelize, Just-In-Time compile to GPU/TPU, and more."

- [JAX - Quick Start](https://jax.readthedocs.io/en/latest/notebooks/quickstart.html)

"JAX is NumPy on the CPU, GPU, and TPU, with great automatic differentiation for high-performance machine learning research."

[JAX é um projeto open source do Google](https://github.com/google/jax) com o objetivo de criar uma API simples e backend eficiente para cálculos de deep learning. Tem crescido em popularidade e sido considerada muito promissora por pesquisadores. Imagina-se que em alguns anos será um concorrente direto do Pytorch (na área de pesquisa), e também deverá substituir o backend do tensorflow (na área de aplicações). Há quem chame o JAX de  "tensorflow 3", e já existem planos para criação de uma API high level para JAX, adaptando a biclioteca Keras para usar JAX como backend. Portanto, é interessante conhecer.


# Transformers
Os Transformers e o Attention Mechanism, propostos em 2017 por Vaswani - Google Brain no paper Attention Is All You Need, são, até hoje, a maior revolução que o mundo do Deep Learning já passou. Vale a pena estudá-los com atenção (pun intended 😆), pois eles são o estado da arte em redes neurais hoje em dia para a maioria dos tasks, e pelo visto continuarão sendo por bastante tempo.

Transformers mostraram que não é preciso usar camadas LSTM para fazer tasks de NLP no estado da arte, e também não precisamos de camadas de Convolução para fazer CV (Computer Vision) no estado da arte. Attention Is All You Need.

### Papers

- [Attention Is All You Need - paper dec/2017](https://arxiv.org/pdf/1706.03762.pdf) - paper original: fundamental ler
- [BERT - paper may/2019](https://arxiv.org/pdf/1810.04805.pdf) - BERT paper
- [RoBERTa - paper jul/2019](https://arxiv.org/pdf/1907.11692.pdf) - RoBERTa paper
- [Longformer - paper dec/2020](https://arxiv.org/pdf/2004.05150.pdf) - paper Longformer - Local Attention (SOTA transfomer model)
- [Vision Transformers (ViT) - paper jun/2021](https://arxiv.org/pdf/2010.11929.pdf) - ViT paper
- [Swin Transformer - paper aug/2021](https://arxiv.org/pdf/2103.14030.pdf) - Swin Transformer paper - Shifted Window based Self-Attention
- [DeBERTa: Disentangled Attention - paper oct/2021](https://arxiv.org/pdf/2006.03654.pdf) - DeBERTa paper


### Outras fontes

- [BERT Attention Mechanism](https://peltarion.com/blog/data-science/self-attention-video) - vídeo
- [Illustrated Guide to Transformers](https://www.youtube.com/watch?app=desktop&v=4Bdc55j80l8) - vídeo
- [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/) - blog & vídeo
- [The Annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html) - explicações sobre o paper Attention Is All You Need
- [Attention implementation in torch from scratch - twitter thread](https://twitter.com/abhi1thakur/status/1470406419786698761) - Abhishek Thakur
- [Attention implementation in torch from scratch - twitter thread 2](https://twitter.com/abhi1thakur/status/1471126502112698368) - Abhishek Thakur
- [Transformers from Scratch](https://e2eml.school/transformers.html) - explicação visual e detalhada


### Vision Transformer (ViT) and others

- [ViT - 5 min video](https://www.youtube.com/watch?v=DVoHvmww2lQ)
- [ViT - Hugging Face](https://huggingface.co/docs/transformers/model_doc/vit)
- [ViT exemplo - tranformer library](https://www.youtube.com/watch?app=desktop&v=Bjp7hebC67E) - vídeo
- [ViT exemplo - timm library](https://www.youtube.com/watch?v=ovB0ddFtzzA) - vídeo
- [Swin Transformer](https://www.youtube.com/watch?v=SndHALawoag) - vídeo

# NLP - Natural Language Processing
Principais conceitos e keywords a conhecer: n-grams, CBOW (Continuous Bag of Words), Word2vec, FastText (facebook model), GloVe (Global Vectors), CountVectorizer, TF-IDF, BERT, RoBERTa, Hugging Face....

- [BERT tutorial by Abhishek Thakur](https://www.youtube.com/playlist?app=desktop&list=PL98nY_tJQXZl0WwsJluhc6tGrKWCX2suH)
- [Hugging Face course](https://huggingface.co/course/chapter1/1) - excelente curso. HF é o melhor ecossistema de NLP e continuará sendo por muitos anos
- [Text Classification from Scratch](https://www.kaggle.com/vanshjatana/text-classification-from-scratch?scriptVersionId=33686389) - @vanshjatana
- [10 Things You Need to Know About BERT and Transformer Architecture](https://neptune.ai/blog/bert-and-the-transformer-architecture-reshaping-the-ai-landscape)
- [A Survey of Transformers - paper jun/2021](https://arxiv.org/pdf/2106.04554.pdf) - paper para consulta
- [Transformers in Tensorflow](https://www.tensorflow.org/text/tutorials/transformer#setup)

# Computer Vision

### Yolo

- [Yolo Introduction](https://www.youtube.com/watch?app=desktop&v=4eIBisqx9_g) - vídeo
- [Face mask yolo-v5 example](https://www.youtube.com/watch?v=12UoOlsRwh8) - vídeo
- [Yolo v5 tutorial - notebook](https://colab.research.google.com/github/ultralytics/yolov5/blob/master/tutorial.ipynb)
- [Yolo tutorial by Abhishek Thakur](https://www.youtube.com/watch?app=desktop&v=NU9Xr_NYslo) - vídeo
- [Yolo v5 github repo - ultralytics](https://github.com/ultralytics/yolov5)
- [Yolo v5 - paper jul/2021](https://arxiv.org/pdf/2104.13634.pdf)

### Basics

- [Kernel size in convolution layers](https://medium.com/analytics-vidhya/significance-of-kernel-size-200d769aecb1)
- [Digit Recognizer: Getting Started Competition](https://www.kaggle.com/c/digit-recognizer) - ‘Hello World’ do mundo de CV: Estudar vários notebooks com bom score, e depois criar o seu misturando várias técnicas que vc achou promissoras em outros notebooks, tentando melhorar o score do baseline. Recomendo no mínimo uns 10 dias de estudo para essa competição.
- [Pytorch tutorial for image classification](https://www.kaggle.com/hinepo/pytorch-tutorial-cv-99-67-lb-99-26) - @hinepo
- [Ensemble for image classification](https://www.kaggle.com/hinepo/ensemble-by-probabilities-lb-99-43) - @hinepo 

### Pytorch image models (timm)

O que o Hugging Face é para NLP é análogo ao que a biblioteca timm é para computer vision: um ecossistema open source, consolidado e no estado da arte, que disponibiliza uma API simples e unificada para uso de modelos, além de centenas de excelentes modelos multi-propósito (multi-task, general purpose models), já pré-treinados durante semanas em GPUs e TPUs de dezenas de milhares de dólares, todos prontos para usarmos apenas adicionando uma última camada na rede neural para atender ao nosso task/problema. Isso se chama feature extraction, e evita que tenhamos que treinar esses modelos gigantes from scratch.

- [timm: pytorch image models](https://github.com/rwightman/pytorch-image-models/tree/master/timm)
- [timm: getting started](https://rwightman.github.io/pytorch-image-models/)
- [timm: overview](https://fastai.github.io/timmdocs/)
- [Pytorch/timm tutorial for transfer learning](https://www.kaggle.com/hinepo/transfer-learning-with-timm-models-and-pytorch) - @hinepo


# MLOps
- [Made With ML](https://madewithml.com/) - website
- [Machine Learning Operations](https://ml-ops.org/) - website
- [MLflow](https://www.youtube.com/watch?app=desktop&v=859OxXrt_TI) - vídeo
- [MLflow on Databricks](https://www.youtube.com/watch?app=desktop&v=nx3yFzx_nHI&t=1260s) - vídeo
- [Weights and biases](https://www.youtube.com/watch?v=krWjJcW80_A) - vídeo


# Youtube channels

Abaixo alguns canais nos quais acho válido se inscrever e acompanhar os conteúdos publicados.

```diff 
Deep Learning
```
- Abhishek Thakur
- AI Coffee Break with Letitia
- Sentdex
- Pysource
- TechViz – The Data Science Guy
- deeplizard
- Tensorflow
- Deeplearning.ai

```diff 
Yolo
```
- The AI Guy

```diff 
AI e conceitos
```
- Krish Naik
- edureka!

```diff 
Sortidos
```
- AIEngineering
- Bhavesh Bhatt
- BI Elite
- Tech with Tim
- Hashtag Treinamentos

# Perfis no Instagram

O instagram pode ser usado como uma poderosa ferramenta de estudo, assim como o twitter. Funciona muito bem como dose diária e homeopática de aprendizado, e ajuda muito a acompanhar o trabalho de outras pessoas e cientistas de dados. Seguir #’s dos assuntos que te interessam também ajuda muito a se manter atualizado. Em ciência de dados as coisas acontecem/andam/mudam muito rápido, e plataformas que te entregam a informação de forma rápida e eficiente costumam ser muito úteis.

Alguns perfis interessantes para seguir:

- flai.inteligencia.artificial
- setimoreino
- technium_lab
- raven.ai_
- analytics_vidhya
- veedha_data_analyst
- sysadmin_impaciente
- coderhumor
- universidadedosdados
- compvidareal
- know_datascience
- devfullcycle
- pythonacademybr
- devops_zoeiro
- philipplackner_official
- python___developers
- dynamic.coding
- coders.eduyear
- tech_with_luciana

- codinggoats
- websitescraper
- justdjangocode
- django.python
- powerbi.tips
- powerbinapratica
- empowerdata
- karinedolago
- entendendobi
- leticiasmirelli
- leokarpa
- google_cloud_training
- googlecloudindia
- r.mlearning
- dougkasmacielc
- fabricio.giordanelli
- justenough_spark

- apiagil
- proffernandamaciel
- techworld_with_nana
- _pythonworld_
- code.forever
- cloudeasy.co
- linux.teach
- linuxnaweb
- dataengineeringworld
- python.for.nerds
- python.advance.projects
- googlecloud
- digitalcloudtraining
- more.programmingacademy
- awssamurai
- dashboarddesign2017
- v7labs
- pysource7
- javascript.js
