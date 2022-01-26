# Anomaly-detection

![oi](https://github.com/RondinellyMorais/Anomaly-detection/blob/master/newplot.png)

Anomalias são itens, eventos raros ou observações incomuns dentro um grande massa de dados. Geralmente dados anômalos indicam problemas pontuais na produção dados ou eventos de fraudes. 

A detecção de anomalias, é neste contexto, fundamental para várias áreas de pesquisa e de mercado, tais como fraude bancaria, defeito estrutural e problemas médicos. Usaremos o método não-supervisionado de classificação de anomalias, onde a detecção é feita sem termos exemplos de dados rotulados. Muitos problemas requer que detectemos anomalais em séries temporais e é isso que faremos neste notebook.

Atualmente dispomos de muitas ferramentas para detecção de anomalias em grandes bases de dados. Aqui aplicaremos algumas delas, avaliando algumas vantagens destas em relação as demais. Usaremos como base de dados de teste um dataset que contem 300000 registros da variação do nível do volume de água de uma represa com o tempo.
