# Classificação de relevância de normas tributárias com machine learning

#### Aluno: [Thiago Magnago Meira](https://github.com/Thiago-Magnago).
#### Orientador: [Cristian Munoz](https://github.com/crismunoz).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

- [Link para o código](https://github.com/Thiago-Magnago/PUC-Rio-BI-Master-TCC/blob/main/NLP_Classifier%20of%20Tax%20Laws.ipynb).


---

### Resumo

Trabalho de construção de uma PoC de um modelo de machine learning para classificação de texto (aprendizado supervisionado), relativo à relevância de normas tributárias brasileiras.

Não é novidade afirmar que o Brasil tem um dos sistemas tributários mais complexos do mundo. Diariamente são publicados um grande número de normas tributárias: De acordo com o IBPT*, O Brasil cria, em média, 46 novas regras tributárias por dia útil.

(*) https://ibpt.com.br/brasil-cria-em-media-46-novas-regras-de-tributos-a-cada-dia-util/. Accesso em: 23-7-2021

E essas normas podem impactar negócios e atividades das empresas. Portanto, todas essas novas normas precisam ser diariamente lidas por especialistas com o objetivo de avaliar alguma necessidade de ação: ajustar uma operação, alterar alíquotas em seus softwares ERP, entre outros.

Após a leitura de cada uma das normas, os especialistas concluem (rotulam):
- Há impacto na empresa => norma tributária relevante => alguma ação precisa ser tomada.
- Não há impacto na empresa => norma tributária irrelevante => nenhuma ação a ser tomada.

Essa leitura diária consome muitas horas de trabalho, e na maioria dos casos os especialistas leem documentos que não são relevantes para a empresa. (Desperdício de tempo!)

Portanto o objetivo é desenvolver um algorítmo para automaticamente classificar normas tributárias estaduais brasileiras, no contexto de uma empresa do ramo de óleo&gás. Acreditamos que no primeiro momento este classificador ajudaria os especialistas a priorizar a leitura dos documentos. Com o passar do tempo, o modelo pode ser melhorado e os especialistas podem sem sentir mais confiantes em suas predições, resultando em menor necessidade de leitura diária.


### Abstract

This work builds a machine learning model PoC (Proof of Concept) using Python for text classification (supervised learning), related to Brazilian tax laws relevancy. 

It is no novelty to affirm that Brazil has one of the more complex tax system in the world. Daily are published a large number of taxation laws: According to IBPT*, Brazil creates, on average, 46 new taxation rules per working day.

(*) https://ibpt.com.br/brasil-cria-em-media-46-novas-regras-de-tributos-a-cada-dia-util/. Access: 2021-7-23.

And these rules may impact on business and activities of the companies. Therefore, all these new laws must be read everyday by experts in order to assess any action: adjust an operation, change aliquots on their ERP software, among others.  

After reading each of them, the experts conclude (label):
- It has impact on the company => taxation law is relevant => any action to be done.
- It doesn’t have impact on the company => taxation law is irrelevant => no action.

This daily reading spends many working hours, and in most cases the experts read documents that are not relevant to the company. (Waste of time!)

So the aim is to develop an algorithm to automatically classify the brazilian state taxation law, on the context of a oil&gas company.  We believe that in a first moment this classifier would help experts to prioritize the documentos to read. As time goes by, the model can be improved and experts may feel more confident about its prediction, resulting in a minor daily reading.


---

Matrícula: 192.671.007

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
