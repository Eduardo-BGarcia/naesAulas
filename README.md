# naesAulas

MVT

Sobre a pasta templates:

    Sempre dentro de cada arquivo template, criar uma pasta com o mesmo nome:
        exemplo website/templates/website/modelo.html

Sobre as páginas:

    Toda vez que criar uma página, precisa criar um View e especificar o tipo dela (ex: TemplateView);

    Depois, criar uma URL, que é associada a uma View;

Comando:
    Para iniciar o servidor:
        python ./manage.py runserver
    
    Para instalar o Django:
        pip install Django==5.2.11

    Prepara o script para atualizar o banco:
        python ./manage.py makenugrations 

    Para subir as atualizações no banco:    
        python ./manage.py migrate
    
    Criar um super usuário no banco: admin admin
        python ./manage.py createsuperuser

    Porta padrão Django: 
        8000

    Site para se basear:
        https://br.weblium.com/templates/demo/small-farm-website-design-4