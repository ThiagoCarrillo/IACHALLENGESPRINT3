# **Projeto OdontoPrev - Detecção de Padrões Comportamentais**

## **Descrição do Projeto**
O projeto OdontoPrev visa utilizar inteligência artificial para identificar padrões comportamentais dos beneficiários de planos odontológicos. O objetivo principal é prever comportamentos de risco antes que sinistros ocorram, permitindo intervenções preventivas para melhorar o atendimento e reduzir custos.

## **Tecnologias Utilizadas**
- **Linguagem de Programação**: Python
- **Bibliotecas de Machine Learning e Data Science**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-Learn
  - TensorFlow/Keras (em desenvolvimento)
- **Modelo de IA Atual**: Random Forest Classifier

## **Arquitetura do Projeto**
1. **Coleta e Organização dos Dados**:
   - Informações dos pacientes (ID, histórico de tratamentos, número de faltas, registro de sinistros).
   - Dados organizados em um DataFrame Pandas.
2. **Análise Exploratória**:
   - Visualização de distribuições de faltas e sinistros.
   - Geração de gráficos para análise de padrões.
3. **Treinamento do Modelo**:
   - Utilização de **Random Forest** para a previsão de sinistros.
   - Separação entre dados de treino (70%) e teste (30%).
4. **Predição e Classificação de Risco**:
   - Modelo calcula a probabilidade de um paciente apresentar sinistro.
   - Classificação em **Baixo Risco, Risco Moderado e Alto Risco**.
5. **Métricas de Avaliação**:
   - Matriz de confusão e relatório de classificação para medir a performance.

## **Próximos Passos**
- Refinamento do modelo de Machine Learning com **Redes Neurais Profundas**.
- Expansão da base de dados para maior precisão.
- Integração com um aplicativo mobile para exibição dos dados.

## **INTEGRANTES DO GRUPO** 
- THIAGO CARRILLO RM553565
- IGOR OVIEDO RM553434
- CAUÃ LOUREIRO RM553093 

## **LINK DO VIDEO**
https://youtu.be/aLQwdijJQ80
