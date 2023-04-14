# type-event
 

### Ativar o ambiente virtual:
> source venv/bin/activate
> venv\Scripts\Activate
>
>
> Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned (executar antes, caso apresente erro)


### Bibliotecas utilizadas:
> pip install django
> pip install pillow

### Instalando app:
> python3 manage.py startapp usuarios
> python3 manage.py startapp eventos


### Executando servidor (amb:local)
> python3 manage.py runserver

### URLs:
> admin/ - Area administrativa
> 
> usuarios/cadastro/ - Cadastro de usuários
> usuarios/login/ - Realizar o login
>
> eventos/novo_evento/ - Cadastro de eventos
> eventos/gerenciar_evento/ - Registro de eventos