# awesome-python-typing

[![Gitter](https://badges.gitter.im/mypy-django/Lobby.svg)](https://gitter.im/mypy-django/Lobby)

Collection of awesome Python types, stubs, plugins, and tools to work with them.


## Contents

- [Static type checkers](#static-type-checkers)
- [Stub packages](#stub-packages)
- [Tools](#tools)
- [Integrations](#integrations)
- [Articles](#articles)
- [Communities](#communities)
- [Related](#related)


## Static type checkers

- [mypy](https://github.com/python/mypy) - optional static typing for Python 3 and 2 (PEP 484).
- [pyre](https://pyre-check.org/) - a performant type-checker for Python 3.
- [pytype](https://github.com/google/pytype) - tool to check and infer types for Python code - without requiring type annotations.
- [PyCharm](https://www.jetbrains.com/pycharm/) - the Python IDE for Professional Developers.
- [pyright](https://github.com/Microsoft/pyright) - a fast type checker meant for large Python source bases. It can run in a “watch” mode and performs fast incremental updates when files are modified.


## Stub packages

- [Typeshed](https://github.com/python/typeshed) - collection of library stubs for Python, with static types.
- [django-stubs](https://github.com/typeddjango/django-stubs) - stubs for [Django](https://github.com/django/django).
- [djangorestframework-stubs](https://github.com/typeddjango/djangorestframework-stubs) - stubs for [DRF](https://github.com/encode/django-rest-framework).
- [numpy-stubs](https://github.com/numpy/numpy-stubs) - stubs for [NumPy](http://github.com/numpy/numpy).
- [dry-python/returns](https://github.com/dry-python/returns) - stubs for [returns](https://github.com/dry-python/returns).
- [sqlalchemy-stubs](https://github.com/dropbox/sqlalchemy-stubs) - stubs for [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy).
- [grpc-stubs](https://github.com/shabbyrobe/grpc-stubs) - stubs for [grpc](https://github.com/grpc/grpc).
- [PyQt5-stubs](https://github.com/stlehmann/PyQt5-stubs) - stubs for [PyQt5](https://www.riverbankcomputing.com/software/pyqt/intro).
- [ordered-set-stubs](https://github.com/rominf/ordered-set-stubs) - stubs for [OrderedSet](https://github.com/LuminosoInsight/ordered-set).
- [pyspark-stubs](https://github.com/zero323/pyspark-stubs) - stubs for [PySpark](https://spark.apache.org/docs/latest/api/python/index.html).


## Tools

### Linters

- [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) - the strictest and most opinionated python linter ever.
- [flake8-mypy](https://github.com/ambv/flake8-mypy) - a plugin for flake8 integrating mypy.
- [flake8-pyi](https://github.com/ambv/flake8-pyi) - a plugin for Flake8 that provides specializations for type hinting stub files.
- [flake8-annotations-complexity](https://github.com/best-doctor/flake8-annotations-complexity) - a plugin for flake8 to validate annotations complexity.

### Testing

- [pytest-mypy](https://github.com/dbader/pytest-mypy) - mypy static type checker plugin for Pytest.
- [pytest-mypy-plugins](https://github.com/typeddjango/pytest-mypy-plugins) - pytest plugin for testing mypy types, stubs, and plugins.

### Working with types

- [MonkeyType](https://github.com/instagram/MonkeyType) - collects runtime types of function arguments and return values, and can automatically generate stub files or even add draft type annotations directly to your Python code based on the types collected at runtime.
- [merge_pyi](https://github.com/google/pytype/tree/master/pytype/tools/merge_pyi) - part of pytype toolchain, applies stub files onto source code.
- [retype](https://github.com/ambv/retype) - another one tool to apply stubs to code.
- [mypy-protobuf](https://github.com/dropbox/mypy-protobuf) - tool to generate mypy stubs from protobufs.

### Mypy plugins

- [pynamodb-mypy](https://github.com/lyft/pynamodb-mypy) - plugin for [PynamoDB](https://github.com/pynamodb/PynamoDB) support.
- [mypy-zope](https://github.com/Shoobx/mypy-zope) - plugin for [zope.interface](https://zopeinterface.readthedocs.io/en/latest/) support.
- [mypy/plugins](https://github.com/python/mypy/tree/master/mypy/plugins) - some plugins already integrated into mypy.


## Integrations

- [mypy-PyCharm-plugin](https://github.com/dropbox/mypy-PyCharm-plugin) - mypy integration for PyCharm.
- [vim-mypy](https://github.com/Integralist/vim-mypy) - mypy integration for Vim.
- [linter-mypy](https://atom.io/packages/linter-mypy) - mypy integration for Atom.
- [emacs-flycheck-mypy](https://github.com/lbolla/emacs-flycheck-mypy) - mypy integration for Emacs.


## Articles

### PEPs

- [PEP-483](https://www.python.org/dev/peps/pep-0483/) about type hints theory.
- [PEP-484](https://www.python.org/dev/peps/pep-0484/) about type annotations.
- [PEP-544](https://www.python.org/dev/peps/pep-0544/) about protocols.
- [PEP-561](https://www.python.org/dev/peps/pep-0561/) about distributing and packaging type information.
- [PEP-563](https://www.python.org/dev/peps/pep-0563/) about postponed evaluation of annotations.
- [PEP-586](https://www.python.org/dev/peps/pep-0586/) about literal types.
- [PEP-3107](https://www.python.org/dev/peps/pep-3107/) about function annotations.

### Tools' docs

- [MyPy docs](https://mypy.readthedocs.io/en/latest/stubs.html) about stubs.

### Third-party articles

- [Typechecking Django and DRF](https://sobolevn.me/2019/08/typechecking-django-and-drf) - full tutorial about type-checking django.
- [Testing mypy stubs, plugins, and types](https://sobolevn.me/2019/08/testing-mypy-types) - full tutorial about testing mypy types.


## Communities

- [python/typing](https://gitter.im/python/typing) gitter chat.
- [TypedDjango](https://gitter.im/mypy-django/Lobby) gitter chat.
- [PythonRu#typing](https://python-ru.slack.com) slack chat (invites are [here](https://slack.python.ru/))


## Related

- [awesome-python](https://github.com/vinta/awesome-python)
- [python-typecheckers](https://github.com/ethanhs/python-typecheckers)


## License

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
