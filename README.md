# Docket-AI-Test

__author__      = "Jeferson S. Pazze"

__description__ = "This code has the algorithms of data preprocessing and inference"

__github__      = "jeff-pazze"

__data__        = "December/2022"

__credits__     = "Docket"

__version__     = "1.1"

__maintainer__  = "Jeferson S. Pazze"

__email__       = "jeff.pazze@gmail.com"

__status__      = "engineer"


<div class="alert alert-block alert-info">
<b>Tip:</b>tips and notes.</div>
     
<div class="alert alert-block alert-warning">
<b>Example:</b>Typically also used to display warning messages.
</div>
    
<div class="alert alert-block alert-success">
<b>Success:</b> This alert box indicates a successful or positive action.
</div>    
     
<div class="alert alert-block alert-danger">
<b>Danger:</b> This alert box indicates a dangerous or potentially negative action.
</div>  


## **Observações**: 🎯
--------

**No decorrer do documento explico a metodologia utilizada, as técnicas em cada etapa entre outros dados que julgo importante para o desenvolvimento de modelos de ML.**

Para a administração do meu tempo utilizei o Azure Devops onde tenho um board com atividades. Distribui cada atividade no periodo de 3 dias (Seg, ter e qua) com um tempo máximo de 2h30m dia.

Reservei 80 % do tempo para o dataprep e modelagem.

Com o tempo que sobrou executei um XAI para explicar o porque que o modelo toma tal decisão, como por exemplo: porquê ele disse que tal review era negativa ou neutra.

<font color="red"> Executei técnicas de balanceamento dos dados, mas como estamos trabalhando em uma base pequena se utilizaremos undersample reduziriamos demais o dataset, já a tecnica de oversample e SMOTE não trouxeram melhoras nos resultados, assim como, pioraram a capacidade do modelo generalizar.



Link para acesso ao drive com o modelo, dataset e jupyter notebook: https://drive.google.com/drive/folders/1N6WYR7ZcW5CD8259okteQS-WxVxCCvj2?usp=share_link

Link para acesso ao github com o modelo, dataset e jupyter notebook: https://github.com/jeff-pazze/Docket-AI-Test





###**PROPOSTA**
---

Neste teste para a área de machine learning, a
partir do briefing e requisito apresentados, a
Docket propõe a você classificar amostras
sobre o mercado de ações.


**IMPORTANTE**

*      Crie um projeto no Google Colab. Permita ele ser acessado por qualquer um com o link;

*      O modelo treinado pode ser salvo em alguma plataforma como Google Drive.Permita também ele ser acessado por qualquer um com o link.



###**BRIEFING**
---

A Docket tem o objetivo de desburocratizar os
serviços cartorários para nossos clientes B2B,
realizando a busca, gestão e pré-análise dos
documentos, assim reduzindo o tempo de
entrega e acompanhando o andamento de seu
pedido através do nosso produto.

**O QUE FAZEMOS**

*     Buscamos documentos em todo o Brasil;

*     Entregamos os documentos aos clientes em até 15 dias;

*     Pré-analisamos documentos de forma automática.



###**REQUISITOS**
---

**CLASSIFICAÇÃO DE AMOSTRAS DE TEXTO**

Atualmente, nossos clientes solicitam ou nos
enviam vários tipos de documentos. A partir
desses documentos, extraímos e selecionamos
diversas informações importantes para eles.
Para que essas informações sejam
corretamente extraídas, um processo
inteligente de classificação do documento é
necessário.
O desafio que a Docket propõe é um problema
de NLP, para classificação de notícias sobre o
mercado de ações, a partir do dataset Stock
Market News.


###**REQUISITOS OBRIGATÓRIOS**
---

● Utilizar o dataset Stock Market News em versão portuguesa;

● Treinar um modelo de machine learning capaz de classificar cada amostra do
dataset como uma das seguintes labels:
*   positiva;
*   negativa;
*   neutra.


###**TECNOLOGIA**
---

USAR AS SEGUINTES TECNOLOGIAS


*   Python;
*   Google Colab;
*   Pacotes de sua preferência.


###**PLANEJAMENTO**
---

Nos conte como irá se planejar para executar o projeto, como por exemplo: como transformou os requisitos em tarefas, se utilizou alguma ferramenta para se organizar, se desenhou algum diagrama, o processo de criação do dataset, porque escolheu certo modelo, etc.
Essa é uma questão livre!


## Metodologia Utilizada
---------
Foi selecionado a metodologia **CRISP-DM** (Cross Industry Standard Process for Data Mining) para a execução deste trabalho.

O objetivo dessa metodologia é desenvolver modelos a partir da análise de informações e dados de um negócio para prever futuras falhas e soluções. Está metodologia está dividida em seis etapas, como é apresentado na sequência.

1.   Entendimento do negócio
2.   Entendimento dos dados
3.   Preparação dos dados
4.   Modelagem dos dados
5.   Avaliação do Modelo
6.   Deployment



1.  **Entendimento do negócio:** A primeira atividade nesta metodologia é entender de fato qual o problema a ser resolvido.

      <font color="red"> Caso ela não seja feita da maneira correta, todo o resto do projeto pode ser invalidado futuramente.</font>


2.   **Entendimento dos dados:** 

      Quantas fontes de dados serão utilizadas? 

      Quais serão os formatos dos dados? 

      Os dados estão estruturados?.
      
      <font color="green"> **A partir destes questionamento é realizado a coleta dos dados, tomando cuidado para que nenhuma informação importante fique de fora.**</font>

      <font color="blue"> **defina → colete → explore**</font>



3.   **Preparação dos dados:** Após a coleta dos dados, é necessário organizá-los de modo que seja possivel identificar o que os mesmos contam. 

      Como os valores nulos devem ser tratados?

      Os atributos estão nos formatos corretos?

      Será necessário fazer alguma fusão com outros dados?

      Quais variáveis serão utilizadas na modelagem?

      <font color="green"> **Geralmente está etapa consome de 70 à 90% de todo o tempo proposto na atividades da CRISP-DM.**</font>

      <font color="red"> **Se esta etapa passar para próxima fase com erros, seu modelo inteiro tem que ser refeito.**</font>
   


4.   **Modelagem dos dados:** Nesta etapa é realizada a criação do modelo.

      Nesta etapa o modelo começa a tomar forma, ou seja, é possivel ver os primeiros resultados. 

      O tipo de modelagem a ser utilizada normalmente é definida de acordo com a necessidade do negócio e com o tipo de variável a ser analisada.

      <font color="blue"> **selecione um método → separe um conjunto de dados para teste → construa o modelo → valide em todas as possibilidades**</font>



5.   **Avaliação do Modelo:** Com a etapa de modelagem finalizada é possivel avaliar se o se o resultado corresponde à expectativa do projeto.



6.   **Deployment (Implementação):** Aqui, o modelo deve ser colocado em produção, de modo a agregar valor para o negócio. 



**Referência:**


https://www.knowsolution.com.br/voce-sabe-o-que-e-metodologia-crisp-dm-descubra-aqui/
https://blog.mbauspesalq.com/2022/04/12/crisp-dm-as-6-etapas-da-metodologia-do-futuro/
https://www.escoladnc.com.br/blog/data-science/metodologia-crisp-dm/
https://www.linkedin.com/pulse/crisp-dm-o-que-%C3%A9-e-como-usar-rodrigo-ribeiro/?originalSubdomain=pt
