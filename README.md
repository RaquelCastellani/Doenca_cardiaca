<span align="center">
<h1> 🫀 Doença cardiaca! 🫀 </h1>
</span>

<p align="center">Modelo preditivo de doença cardíaca</p>


## **Documentação** 

* **Idade**: em anos
* **Sexo**: o sexo da pessoa
    - **1**: masculino
    - **0**: feminino
* **Tipo**: tipo de dor torácica
 - **0**: assintomático
 - **1**: angina atípica
 - **2**: dor não anginosa
 - **3**: angina típica
* **Pa repouso**: A pressão arterial em repouso da pessoa (mm Hg na admissão ao hospital)
* **Colesterol**: a medição de colesterol da pessoa em mg/dl
* **Glicemia**: glicemia em jejum da pessoa > 120 mg/dl
    - **1** = verdadeiro
    - **0** = falso
* **Ecg repouso**: resultados eletrocardiográficos de repouso
    - **0**: mostrando provável ou definitiva hipertrofia ventricular esquerda
    - **1**: normal
    - **2**: com anormalidade da onda ST-T (inversões da onda T e/ou elevação ou depressão de ST > 0,05 mV )
* **Fc max**: A frequência cardíaca máxima da pessoa alcançada
* **Exercicio**: angina foi induzida pelo exercício
    - **1**: sim
    - **0**: não
* **Oldpeak**: depressão de ST induzida pelo exercício em relação ao repouso ('ST' refere-se a posições no gráfico de ECG.)
* **Inclinacao**: a inclinação do segmento ST do exercício de pico 
    - **0**: inclinação descendente
    - **1**: plano
    - **2**: ascendente
* **Veias**: o numero de veias
* **Talessemia**: Um distúrbio do sangue chamado talassemia 
    - **0**: sem informação
    - **1**: defeito fixo (sem fluxo sanguíneo em alguma parte do coração)
    - **2**: fluxo sanguíneo normal
    - **3**: defeito reversível (é observado um fluxo sanguíneo mas não é normal)
* **Output**: Doença cardíaca
    - **1**: não
    - **0**: sim

## **Proposta** 

A partir de dados retirados do Kaggle, realizei uma ánalise exploratória para melhor compreensão e realizei um modelo de previsão de doenças cardíacas.

## **Bibliotecas utilizadas**

Para realização desse projeto utilizei as bibliotecas Pandas, Matplotlib, Seaborn, Pycaret e Sklearn.

## **Planos futuros** 

Estudar um pouco mais o dataset original a fim de entender melhor a coluna 'caa' que no caso seria 'veias'. E irei realizar outro modelo preditivo utilizando TensorFlow.
