# Mini Curso sobre Django

Olá, tudo joia? Esse repositório aborda o passo a passo na criação de um blog utilizando Python e o Django Framework. Vamos aprender juntos?

Precisamos baixar e instalar o Python na versão 3.5 ou superior no site oficial [Python](https://www.python.org/downloads/), logo após isso podemos continuar.

Com o Python instalado nós vamos utilizar uma ferramenta muito importante no desenvolvimento com python, é o Virtualenv. Para um melhor entendimento, o Virtualenv é um meio de isolar as dependências de um projeto específico e isso vai facilitar e muito a nossa vida, no decorrer deste mini curso isso ficará claro!

Vamos criar o nosso ambiente virtual e ativa-lo:
```shell
python3 -m venv env && source env/bin/activate
```

Se tudo ocorreu bem, no seu console de comando, deverá aparecer algo como:
```shell
(env) $
```

Isso indica que nosso ambiente virtual está instalado e ativado. Podemos então instalar nossa unica dependência do momento, o Django 1.9.2. Execute o comando abaixo:
```shell
pip install django==1.9.2
```

Fantástico! Agora nós temos o Django instalado em nosso ambiente virtual de desenvolvimento! Não fique intimidado por executar tantos comandos, ao passar do tempo nós ganharemos mais familiaridade com esses comandos.

Tudo perfeito até o momento (wow) mas agora nós precisamos iniciar de fato o nosso desenvolvimento, certo?
```shell
django-admin startproject meusite
```
Muito simples! Acabamos de criar um novo projeto chamado de **meusite** e temos uma estrutura de pastas e arquivos como mostrado logo abaixo.

```shell
├── manage.py
└── meusite
    ├── __init__.py
    ├── settings.py
    ├── urls.py
    └── wsgi.py
```

Por enquanto é só, até a próxima.

[Segunda parte](https://github.com/joffilyfe/django-for-humans/tree/0.0.2)

