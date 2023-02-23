Material desenvolvido como atividade da Mentoria com João Oliveira e material da Maratona Python com Power BI disponível YouTube  pelo professor Joviano Silveira.

Consiste na elaboração de Dashboard com indicadores da performace dos vereadores da Câmara Municipal de Indaial em Santa Catarina para auxiliar a ONG Observatório Social no acompanhamento dos projetos feitos, status, áreas impactadas e afins para melhoria da gestão pública.

Para isso, utilizando Web Scraping  (coleta de informações da internet) com Python , foram buscados dados de indicações de Vereadores no site da Câmara, considerando o período de 1996 a 2021. Os dados foram salvos em um banco de dados SQL Server e após foi feito o painel visual com os indicadores utilizando Microsoft Power BI.

Seguem as bibliotecas e programas utilizados, para o desenvolvimento do Projeto:

1- Python

Bibliotecas:
python -m pip install pip==20.3.1 <br> 
pip install jupyterlab==2.2.9 <br> 
pip install numpy==1.18.3  <br>
pip install pandas==1.1.5  <br>
pip install matplotlib==3.3.3 <br>
pip install seaborn==0.11.0 <br>
pip install openpyxl==3.0.5 <br>
pip install xlrd==1.2.0 <br><br>

Bibliotecas especifícas para webscrapping nesse projeto:<br>
pip install beautifulsoup4==4.9.3 <br>
pip install html5lib==1.1 <br>
pip install requests==2.25.1 <br>
pip install lxml==4.6.2 <br><br>

2- Para o Banco de Dados:
•	SQL Server Developer Edition;<br>
•	SSMS – Microsoft Management Studio;<br>

3- Para o Dashboard
•	Power BI – a versão mais;<br>




