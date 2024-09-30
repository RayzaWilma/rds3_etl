
# rds3_etl
### Repositório com arquivos que foram utilizados na palestra da terceira edição do Recife Data Saturday sobre ETL no Pentaho e Databricks.
<br>


Explicação do objetivo de cada arquivo:
<br>

- **transform_rds3.ktr:** arquivo com transformações para ser utilizado com o Pentaho;
- **recife_data_saturday_3.dbc:** notebook para ser importado no Databricks;
- **Lista de participantes - Recife_Data_Saturday_3:** arquivo tanto em XLS, como CSV para testes (foi deixado apenas alguns registros para testes e alterado os valores principais para evitar identificação de dados pessoais). 

Clicando [neste link](https://bigdatanavigators.com/2024/09/30/databricks-como-realizar-cadastro-no-community-e-utiliza-lo-gratuitamente/), você tem acesso ao tutorial que criei para se cadastrar no Databricks Community e poder utilizá-lo gratuitamente, onde deixei um passo a passo bem explicativo.
<br>

---
<br>

No **Pentaho**, ao abrir o arquivo **transform_rds3.ktr** será necessário clicar no step **"src_evento_rds3"**, clicar em **"Navegar"**, buscar o arquivo **"Lista de participantes - Recife_Data_Saturday_3.xls"** que será utilizado como fonte e clicar em **ADD** para que o mesmo apareça nos arquivos selecionados conforme o print abaixo: 


![424a3593-d3a2-4002-992e-d4ca27baa320](https://github.com/user-attachments/assets/67d8e78d-4ca0-458d-9f72-45afabf87fdb)


<br>

---
<br> 

No Databricks, basta ir em seu Workspace, clicar com o botão direito (ou nos 3 pontinhos que aparecem) e clicar em **"Importar"**. Selecione o notebook **"recife_data_saturday_3.dbc"** e importe o mesmo. 

![583c2e65-041c-4b21-a982-b49c7a98e465](https://github.com/user-attachments/assets/4bbf649f-3bbb-4aa7-80f1-09a9122df4f5)
![a9a2dfaf-c5da-4653-94b4-76eeb2f948aa](https://github.com/user-attachments/assets/731269d5-7ca3-404b-a44a-032440fa5265)


<br>

Também será necessário realizar a importação do arquivo para dentro do Databricks. 
Clique em "Catalog" > "Create Table" e realize o upload conforme print abaixo.


![image](https://github.com/user-attachments/assets/01af212b-4069-49da-a4c8-7c60e5884106)
![image](https://github.com/user-attachments/assets/98af9152-3f24-46a5-b45b-d8bb8318a061)

Após esses procedimentos, basta voltar para o notebook eem seu workspace e seguir com os testes...  =)

Qualquer dúvida podem entrar em contato comigo!

Abraço!
