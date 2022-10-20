Sphinx-Pydantic-SQLAlchemy
---------------------------

Document SqlAlchemy models with sphinx using pydantic.
Supports direct fallback to pydantic models.

This module is intended for quick database model documentation.

It currently supports the following database orms:

- `pydantic-aioredis <https://github.com/andrewthetechie/pydantic-aioredis/>`_
- `odmantic <https://art049.github.io/odmantic/>`_
- `SQLAlchemy <https://www.sqlalchemy.org>`_


|pypi| |release| |downloads| |python_versions| |coverage| |pypi_versions| |actions|

.. |pypi| image:: https://img.shields.io/pypi/l/sphinx-pydantic-sqlalchemy
.. |release| image:: https://img.shields.io/librariesio/release/pypi/sphinx-pydantic-sqlalchemy
.. |downloads| image:: https://img.shields.io/pypi/dm/sphinx-pydantic-sqlalchemy
.. |python_versions| image:: https://img.shields.io/pypi/pyversions/sphinx-pydantic-sqlalchemy
.. |pypi_versions| image:: https://img.shields.io/pypi/v/sphinx-pydantic-sqlalchemy


Examples
--------

.. code:: rst 

   sqla-pydantic:: your.module.your.sqlalchemy.table

References
----------

I initially made this plugin due to lack of support on non-declarative 
sqlalchemy models on `sphinx-sqlalchemy
<https://sphinx-sqlalchemy.readthedocs.io/en/latest/>`_.

After an initial approach with sqlalchemy-pydantic, I realized this had he
potential to document the rest of the databases I'm using with ORMs (redis,
mongo), effectively making this a library capable of autodocumenting the whole
set of usual databases (redis, mongo, postgres, mysql, sqlite).

Notes
------

I like :star:, star this project to show your appreciation! 


.. raw:: html

        <a href="https://github.com/XayOn/sphinx-pydantic-sqlalchemy/graphs/contributors">
          <img src="https://contributors-img.web.app/image?repo=XayOn/sphinx-pydantic-sqlalchemy" />
        </a>

Made with `contributors-img <https://contributors-img.web.app>`_
