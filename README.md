# Datathon

## Preparação e Consolidação dos Dados

Devido a dificuldades técnicas encontradas na manipulação dos dados utilizando **Python com Pandas**, o grupo optou por realizar o processo de **limpeza, transformação e consolidação das bases diretamente no Excel**, utilizando o **Power Query**.

O arquivo responsável por esse processo pode ser encontrado no caminho:

```
data/PEDE_ALL.xlsx
```

Neste arquivo foi realizada a **integração das bases referentes aos três anos do dataset**, consolidando-as em uma única estrutura de dados padronizada.

### Etapas de Limpeza e Transformação

Para visualizar todas as etapas do processo de tratamento dos dados:

1. Abra o arquivo **PEDE_ALL.xlsx**
2. Acesse a guia **Dados**
3. Clique em **Obter Dados**
4. Selecione **Iniciar Editor do Power Query**

No **Power Query**, é possível acompanhar detalhadamente todas as etapas aplicadas na preparação dos dados, incluindo:

* Importação das bases originais
* Padronização de colunas
* Ajustes de tipos de dados
* Consolidação das bases anuais
* Transformações necessárias para análise

### Visualização e Ajustes no Power BI

O arquivo:

```
datathon.pbix
```

contém o **dashboard e as análises desenvolvidas para o Datathon**.

Dentro do Power BI, o **Power Query** também foi utilizado para realizar alguns **ajustes adicionais na modelagem dos dados**, necessários para a construção das visualizações e indicadores analíticos.

Esses ajustes incluem principalmente:

* refinamento de colunas
* criação de campos auxiliares
* preparação dos dados para visualização

---

Dessa forma, todo o pipeline de preparação dos dados pode ser facilmente reproduzido e auditado tanto no **Excel (Power Query)** quanto no **Power BI**.
