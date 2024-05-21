# EIACD_Project2
Trabalho 2 de EIACD sobre Data exploration and enrichment for supervised classification para The Hepatocellular Carcinoma Dataset
by Pedro Paulo Rosa Prado Basilio, Adelino Quaresma Moniz da Vera Cruz, Pedro Antonio Resende Gulart

Como Executar
Certifique-se de ter o arquivo hcc_dataset.csv no mesmo diretório que o script Python.
E execute $'python3 SupervisedMain.py' no terminal.
Pare executar o arquivo streamlit utilize o seguinte comando  'streamlit run Supervised_app_streamlit.py' e então conecte-se ao servidor local.

A função execute_parameters aceita os seguintes parâmetros:

na_solution (str): Método de substituição de valores ausentes ('median' ou 'mean').
smote (int): Flag para aplicar SMOTE para balanceamento de classes (1 para aplicar, 0 para não aplicar).
outliner (int): Flag para detectar e substituir outliers (1 para aplicar, 0 para não aplicar).
tt_split (float): Proporção de divisão entre treino e teste (ex: 0.3 para 30% teste, 70% treino).
k_for_cleaning (int): Número de atributos mais correlacionados a serem mantidos.
clean_data_correlation (bool): Flag para limpar dados com base em correlação (True para limpar, False para não limpar).
dstree (int): Flag para habilitar o uso de árvore de decisão (1 para habilitar, 0 para não habilitar).
nodes_for_tree (int): Número máximo de nós na árvore de decisão.
random_frst (int): Flag para habilitar o uso de Random Forest (1 para habilitar, 0 para não habilitar).
kapann (int): Flag para habilitar o uso de KNN (1 para habilitar, 0 para não habilitar).
k_for_knn (int): Número de vizinhos para KNN.
graphs (int): Flag para exibir gráficos (1 para exibir, 0 para não exibir).
shwdata (int): Flag para exibir dados de avaliação (1 para exibir, 0 para não exibir).
seed (int): Semente para geração de números aleatórios.

Observações
Certifique-se de ajustar os parâmetros de acordo com suas necessidades específicas.
Os gráficos e as avaliações são exibidos apenas se graphs ou shwdata forem definidos como 1.
Os resultados dos modelos são apresentados com métricas de avaliação como Accuracy, ROC AUC, Precision, Recall e F1 Score.
Sinta-se à vontade para modificar e experimentar diferentes configurações para obter os melhores resultados para seu caso de uso.

Requirements: 
altair==4.2.2
attrs==23.2.0
blinker==1.8.2
cachetools==5.3.3
certifi==2024.2.2
charset-normalizer==3.3.2
choice==0.1
click==8.1.7
contourpy==1.2.1
cycler==0.12.1
entrypoints==0.4
Extended-BoxPlots==0.3.0
fonttools==4.51.0
gitdb==4.0.11
GitPython==3.1.43
idna==3.7
imbalanced-learn==0.12.2
imblearn==0.0
Jinja2==3.1.4
joblib==1.4.2
jsonschema==4.22.0
jsonschema-specifications==2023.12.1
kiwisolver==1.4.5
markdown-it-py==3.0.0
MarkupSafe==2.1.5
matplotlib==3.9.0
mdurl==0.1.2
numpy==1.26.4
packaging==24.0
pandas==2.2.2
patsy==0.5.6
pillow==10.3.0
plotly==5.22.0
protobuf==4.25.3
pyarrow==16.1.0
pydeck==0.9.1
Pygments==2.18.0
pyparsing==3.1.2
python-dateutil==2.9.0.post0
python-decouple==3.8
pytz==2024.1
referencing==0.35.1
requests==2.31.0
rich==13.7.1
rpds-py==0.18.1
scikit-learn==1.4.2
scipy==1.13.0
seaborn==0.13.2
six==1.16.0
smmap==5.0.1
statsmodels==0.14.2
streamlit==1.34.0
streamlit-aggrid==1.0.5
tenacity==8.3.0
threadpoolctl==3.5.0
toml==0.10.2
toolz==0.12.1
tornado==6.4
typing_extensions==4.11.0
tzdata==2024.1
urllib3==2.2.1
watchdog==4.0.0
