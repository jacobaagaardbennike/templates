
<pre>
./
└── cmd/
  └── api/
    ├── __init__.py
    ├── api.py
  └── dev/
    ├── __init__.py
    ├── start_api_local.py
  ├── __init__.py
└── internal/
  └── <i>domain folders</i>/
    └── migrations/
      ├── <i>Generated files</i>
    ├── __init__.py
    ├── <i>Generated Django files</i>
    ├── admin.py
    ├── api.py
    ├── apps.py
    ├── models.py
    ├── schemas.py
    ├── tests.py
    ├── views.py
  └── platform/
    └── db/
      └── migrations/
        ├── <i>Generated files</i>
      ├── __init__.py
      ├── <i>Generated Django files</i>
    └── django_config/
      ├── __init__.py
      ├── asgi.py
      ├── settings.py
      ├── session.py
      ├── urls.py
      ├── wsgi.py
├── .env
├── .gitignore
├── docker-compose-dev.yml
├── poetry.lock
├── pyproject.toml
├── README.md
</pre>

Bold like migration files and domain folders indicate that they will change with the project. A domain folder could be "plant". Italic indicates that these are optional folders and files you may not have in your project.
