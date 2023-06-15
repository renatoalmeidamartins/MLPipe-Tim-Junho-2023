# Infos de contato para obtenção do voucher de certificação
Jonathan Asti - jonathan.asti@flane.com.pe<br>
+51977724713 - Skype: jon.asti.c

# Exercícios
- [Formulação do problema](https://github.com/renatoalmeidamartins/MLPipe-Tim-Junho-2023/blob/main/Problem%2BFormulation%2BExercise.docx)
- [Formulação do problema - solução](https://github.com/renatoalmeidamartins/MLPipe-Tim-Junho-2023/blob/main/Problem%2BFormulation%2BExercise%2BSolutions.docx)
- [Modelo de projeto](https://github.com/renatoalmeidamartins/MLPipe-Tim-Junho-2023/blob/main/Student%20Project%20Template.docx)
- Notebooks iniciais para cada projeto:
  - [Fraude de cartão](https://github.com/renatoalmeidamartins/MLPipe-Tim-Junho-2023/blob/main/Credit_Card_Fraud_Detection-Student.ipynb)
  - [Atrasos de vôo](https://github.com/renatoalmeidamartins/MLPipe-Tim-Junho-2023/blob/main/Flight_Delay-Student.ipynb)
  - [Recomendações](https://github.com/renatoalmeidamartins/MLPipe-Tim-Junho-2023/blob/main/Amazon_Reviews-Student.ipynb)


# Links do dia 1

- Versoes do material - https://releases.awstc.com/?lang=EN
- Acesso ao ambiente de lab  - https://us-east-1.student.classrooms.aws.training/class/qMC5D4jxg3vVYuJQYcZtGg
- Questionário inicial - https://amazonmr.au1.qualtrics.com/jfe/form/SV_0052a3eXy2Jnkbj
- Skill builder - https://skillbuilder.aws/
- Preparacao de machine learning no skil builder - https://explore.skillbuilder.aws/learn/course/12469/aws-certified-machine-learning-specialty-official-practice-question-set-mls-c01-english
- Infos do exame de ML (com link para guia do exame e questoes de exemplo) - https://aws.amazon.com/certification/certified-machine-learning-specialty/ 
- Learning path de ML - https://aws.amazon.com/training/learning-paths/machine-learning/exam-preparation/
- Artigo bem interessante sobre LLMs e open-source - https://www.schneier.com/blog/archives/2023/06/open-source-llms.html
- Zoologico de redes neurais - https://www.asimovinstitute.org/neural-network-zoo/
- Kaggle, com projetos, competicoes e datasets - https://www.kaggle.com/
- AWS Data Exchange - https://aws.amazon.com/marketplace/search/results?category=d5a43d97-558f-4be7-8543-cce265fe6d9d&FULFILLMENT_OPTION_TYPE=DATA_EXCHANGE&filters=FULFILLMENT_OPTION_TYPE&ref_=adx_hp_hr_brw&trk=adx_hp_hr_brw
- Accuracy, recall, F1 (formas de avaliacao do modelo) - https://towardsdatascience.com/understanding-accuracy-recall-precision-f1-scores-and-confusion-matrices-561e0f5e328c
- Repositório de exemplos do Sagemaker - https://github.com/aws/amazon-sagemaker-examples
- Baseado no acima, com mais doc no readthedocs.io - https://sagemaker-examples.readthedocs.io/en/latest/
- readthedocs do SDK - https://sagemaker.readthedocs.io/en/stable/
- Algoritmos embarcados no sagemaker - https://docs.aws.amazon.com/sagemaker/latest/dg/algorithms-choose.html

# Links do dia 2
- Na execução do lab, em caso de erro para importar `CSVSerializer`, substitua `from sagemaker.predictor import CSVSerializer` por `from sagemaker.serializers import CSVSerializer`
- Hiperparametros do XGBoost - https://docs.aws.amazon.com/sagemaker/latest/dg/xgboost_hyperparameters.html
- Formatos suportados de dados para treinamento - https://docs.aws.amazon.com/sagemaker/latest/dg/cdf-training.html
- Questionário de checkpoint - https://amazonmr.au1.qualtrics.com/jfe/form/SV_7aH7TW8Dwndo9gN
- Sagemaker Canvas para avaliacao de desempenho de modelo - https://docs.aws.amazon.com/sagemaker/latest/dg/canvas-scoring.html
- S3 transfer acceleration speed test - https://s3-accelerate-speedtest.s3-accelerate.amazonaws.com/en/accelerate-speed-comparsion.html
- SMOTE (uma tecnica para lidar com amostras enviesados) - https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.SMOTE.html
- SimpleImputer (classe do scikit para gerar valores adicionados) - https://scikit-learn.org/stable/modules/generated/sklearn.impute.SimpleImputer.html
- GANs (redes neurais para geração de dados para aumentar amostras) - https://towardsdatascience.com/how-to-build-gans-to-synthesize-data-64334b877f70
- Fazendo validação de K-fold no Sagemaker - https://aws.amazon.com/blogs/architecture/field-notes-build-a-cross-validation-machine-learning-model-pipeline-at-scale-with-amazon-sagemaker/
- Definições de validação de modelo - https://docs.aws.amazon.com/sagemaker/latest/dg/how-it-works-model-validation.html
- Usando Scikit-learn para k-fold e estratificação de dados de treinamento - https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html 
- Bring your model using scripts to Sagemaker - https://aws.amazon.com/blogs/machine-learning/bring-your-own-model-with-amazon-sagemaker-script-mode/

  # Links do dia 3
  - biblioteca de pre-processamento do scikit-learn (com inumeros tipos de scaler disponiveis). Atencao especial para os discutidos no material MinMax, MaxAbs, RobustScaler - https://scikit-learn.org/stable/modules/classes.html#module-sklearn.preprocessing
