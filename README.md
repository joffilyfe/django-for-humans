# Mini Curso sobre Django

Vamos dar continuidade ao nosso curso. Na etapa anterior nós iniciamos o nosso projeto e o chamamos de **meusite** e o Django criou uma estrutura para utilizarmos já com alguns arquivos dentro. 

Atualmente nossa estrutura é como está mostrada logo a baixo. Note que temos duas pastas chamadas de **meusite**, a primeira pasta guarda toda a estrutura do nosso projeto e a segunda pasta guarda alguns arquivos *principais* como o settings.py e o urls.py.

```shell
meusite
├── README.md
├── manage.py
└── meusite
    ├── __init__.py
    ├── settings.py
    ├── urls.py
    └── wsgi.py
```
Precisamos entender que o Django trabalha com o conceito de aplicações modulares, dentro de um projeto global nós teremos várias aplicações que podem ou não se comunicarem, o que é o caso do nosso blog. O nosso blog será uma única aplicação dentro de um projeto maior chamado de **meusite**.
De agora em diante nós vamos trabalhar bastante com o arquivo `manage.py`, por meio dele executaremos vários comandos vitais para sincronizar o banco de dados, coletar arquivos estáticos, gerar super usuários e muitas outras coisas. Vamos então criar nosso **app** chamado de **blog**.

```shell
python manage.py startapp blog
```

O django criará uma nova pasta chamada de blog com vários outros arquivos dentro, teremos algo como isto:
```shell
.meusite
├── blog
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── migrations
│   │   └── __init__.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── manage.py
└── meusite
    ├── __init__.py
    ├── settings.py
    ├── urls.py
    └── wsgi.py
```

Ficamos por aqui, até a próxima!

0.0.2

