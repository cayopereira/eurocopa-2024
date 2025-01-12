<h1>Análise de dados da Eurocopa 2024</h1>
<p>
<img src="https://img.shields.io/badge/status-em%20desenvolvimento-green"</>
</p>
<h2>Sobre</h2>
<p>Projeto de análise dos principais jogos da Eurocopa 2024 utilizando a base de dados da [Hudl StatsBomb](https://statsbomb.com/).</p>
<h2>Instalação</h2>

É recomendado criar um ambiente virtual para rodar o projeto por se tratar de uma boa prática de programação. 
Caso esteja utilizando o Linux, abra o terminal na pasta onde se encontra o projeto e rode os seguintes comandos:

```
sudo pip install virtual env
python3 -m venv venv
```
Então, ative o ambiente virtual

```
source venv/bin/activate
```
Em seguida, instale as bibliotecas e pacotes utilizados no projeto. 

```
pip install jupyter
pip install pandas
pip install seaborn
pip install statsbombpy
pip install mplsoccer
pip install highlight_text

```

Sugestão: utilize o arquivo instalar_pacotes.sh para realizar as instalações. 
Basta rodar no terminal o comando

```
chmod +x instalar_pacotes.sh

```