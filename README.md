# Django-basico

Projeto Django-basico - curso Geek University


## Projeto apenas para fins **didáticos** não é um projeto **"real"** ##


Desenvolvido com Django 3.0 - Python 3.8 - MariaDB/MySQL 10.1.43

-------------------------------------------------------------------------

## Como rodar o projeto? ##

```
git clone https://github.com/Hp2501/Django-basico.git
cd Django-basico
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Obs: configurar o *__python-decouple__* e *__dj_database_url__*


[como configurar](https://samuelgoncalves.com.br/configurar-sua-aplicacao-django-para-ler-dados-diferentes-por-ambiente/)


## Conhecimentos aplicados no Projeto ##


* Criando app django e conhecendo sua estrutura
* Padrão MTV do Django
* Configurando Django e o arquivo settings
* Views no Django e o arquivo views
* Rotas no Django e o arquivo urls
* Templates no Django
* Area /admin do Django e o arquivo admin.py 
* Trabalhando com o Django shell
* Apresentando dados do banco de dados no template
* Arquivos estáticos no Django: Css, Javascript, Imagens
* Deploy no Heroku
