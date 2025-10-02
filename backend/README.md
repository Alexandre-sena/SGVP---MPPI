# SGVP-MPPI

Este é o projeto inicial do SGVP-MPPI, uma aplicação desenvolvida em Django REST Framework.

## Estrutura do Projeto

```
SGVP-MPPI/
├── backend/
│   ├── core/
│   │   ├── migrations/
│   │   ├── __init__.py
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── models.py
│   │   ├── tests.py
│   │   └── views.py
│   ├── users/
│   │   ├── migrations/
│   │   ├── __init__.py
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── models.py
│   │   ├── tests.py
│   │   └── views.py
│   ├── manage.py
│   ├── requirements.txt
│   └── settings.py
└── README.md
```

## Instalação

1. Clone o repositório.
2. Navegue até o diretório backend.
3. Instale as dependências com `pip install -r requirements.txt`.
4. Aplique as migrações com `python manage.py migrate`.
5. Inicie o servidor com `python manage.py runserver`. 
