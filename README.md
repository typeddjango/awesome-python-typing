# Awesome Python Typing [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![Gitter](https://img.shields.io/gitter/room/mypy-django/Lobby?color=9cf&style=flat-square)](https://gitter.im/mypy-django/Lobby)

Collection of awesome Python types, stubs, plugins, and tools to work with them.


## Contents

- [Static type checkers](#static-type-checkers)
- [Dynamic type checkers](#dynamic-type-checkers)
- [Stub packages](#stub-packages)
- [Backports and improvements](#backports-and-improvements)
- [Tools](#tools)
- [Integrations](#integrations)
- [Articles](#articles)
- [Communities](#communities)
- [Related](#related)


## Static type checkers

- [mypy](https://github.com/python/mypy) - Optional static typing for Python 3 and 2 (PEP 484).
- [pyre](https://pyre-check.org/) - Performant type-checker for Python 3.
- [pytype](https://github.com/google/pytype) - Tool to check and infer types for Python code - without requiring type annotations.
- [PyCharm](https://www.jetbrains.com/pycharm/) - IDE for Professional Developers.
- [pyright](https://github.com/Microsoft/pyright) - Fast type checker meant for large Python source bases. It can run in a “watch” mode and performs fast incremental updates when files are modified.

## Dynamic type checkers

- [pytypes](https://github.com/Stewori/pytypes) - Provides a rich set of utilities for runtime typechecking.
- [pydantic](https://github.com/samuelcolvin/pydantic) - Data parsing using Python type hinting. Supports dataclasses.
- [typeguard](https://github.com/agronholm/typeguard) - Another one runtime type checker.
- [typical](https://github.com/seandstewart/typical/) - Data parsing and automatic type-coercion using type hinting. Supports dataclasses, standard classes, function signatures, and more.

## Stub packages

- [Typeshed](https://github.com/python/typeshed) - Collection of library stubs for Python, with static types.
- [django-stubs](https://github.com/typeddjango/django-stubs) - Stubs for [Django](https://github.com/django/django).
- [djangorestframework-stubs](https://github.com/typeddjango/djangorestframework-stubs) - Stubs for [DRF](https://github.com/encode/django-rest-framework).
- [numpy-stubs](https://github.com/numpy/numpy-stubs) - Stubs for [NumPy](http://github.com/numpy/numpy).
- [dry-python/returns](https://github.com/dry-python/returns) - Stubs for [returns](https://github.com/dry-python/returns).
- [sqlalchemy-stubs](https://github.com/dropbox/sqlalchemy-stubs) - Stubs for [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy).
- [grpc-stubs](https://github.com/shabbyrobe/grpc-stubs) - Stubs for [grpc](https://github.com/grpc/grpc).
- [boto3-stubs](https://github.com/vemel/mypy_boto3_builder) - Stubs for [boto3](https://github.com/boto/boto3).
- [PyQt5-stubs](https://github.com/stlehmann/PyQt5-stubs) - Stubs for [PyQt5](https://www.riverbankcomputing.com/software/pyqt/intro).
- [ordered-set-stubs](https://github.com/rominf/ordered-set-stubs) - Stubs for [OrderedSet](https://github.com/LuminosoInsight/ordered-set).
- [pyspark-stubs](https://github.com/zero323/pyspark-stubs) - Stubs for [PySpark](https://spark.apache.org/docs/latest/api/python/index.html).
- [pythonista-stubs](https://github.com/hbmartin/pythonista-stubs) - Stubs for [Pythonista](http://omz-software.com/pythonista/docs/ios/).
- [wsgitypes](https://github.com/shabbyrobe/wsgitypes) - Typing for WSGI application implementers. These are not stub files, they're interfaces you mark support for to help typecheck WSGI conformance.

## Backports and improvements

- [typed-ast](https://github.com/python/typed_ast) - Modified fork of CPython's ast module that parses `# type:` comments.
- [typing-extensions](https://github.com/python/typing/tree/master/typing_extensions) - Backported and experimental type hints.
- [typingplus](https://github.com/contains-io/typingplus/) - Backport support, dynamic is_instance and cast for abstract types.
- [typet](https://github.com/contains-io/typet) - Length-bounded types, dynamic object validation. 

## Tools

### Linters

- [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) - The strictest and most opinionated python linter ever.
- [flake8-mypy](https://github.com/ambv/flake8-mypy) - Plugin for flake8 integrating mypy.
- [flake8-pyi](https://github.com/ambv/flake8-pyi) - Plugin for Flake8 that provides specializations for type hinting stub files.
- [flake8-annotations-complexity](https://github.com/best-doctor/flake8-annotations-complexity) - Plugin for flake8 to validate annotations complexity.
- [flake8-annotations](https://github.com/python-discord/flake8-annotations) - Plugin for flake8 to check for presence of type annotations in function definitions.

### Testing

- [pytest-mypy](https://github.com/dbader/pytest-mypy) - Mypy static type checker plugin for Pytest.
- [pytest-mypy-plugins](https://github.com/typeddjango/pytest-mypy-plugins) - Pytest plugin for testing mypy types, stubs, and plugins.

### Working with types

- [MonkeyType](https://github.com/instagram/MonkeyType) - Collects runtime types of function arguments and return values, and can automatically generate stub files or even add draft type annotations directly to your Python code based on the types collected at runtime.
- [merge_pyi](https://github.com/google/pytype/tree/master/pytype/tools/merge_pyi) - Part of pytype toolchain, applies stub files onto source code.
- [retype](https://github.com/ambv/retype) - Another tool to apply stubs to code.
- [mypy-protobuf](https://github.com/dropbox/mypy-protobuf) - Tool to generate mypy stubs from protobufs.
- [mypyc](https://github.com/python/mypy/tree/master/mypyc) - Compiles mypy-annotated, statically typed Python modules into CPython C extensions.
- [typing_inspect](https://github.com/ilevkivskyi/typing_inspect) - The typing_inspect module defines experimental API for runtime inspection of types defined in the Python standard typing module.
- [typing-json](https://pypi.org/project/typing-json/) - Lib for working with typed objects and JSON.   

### Mypy plugins

- [pynamodb-mypy](https://github.com/lyft/pynamodb-mypy) - Plugin for [PynamoDB](https://github.com/pynamodb/PynamoDB) support.
- [mypy-zope](https://github.com/Shoobx/mypy-zope) - Plugin for [zope.interface](https://zopeinterface.readthedocs.io/en/latest/) support.
- [mypy/plugins](https://github.com/python/mypy/tree/master/mypy/plugins) - Plugins already integrated into mypy.


## Integrations

- [mypy-PyCharm-plugin](https://github.com/dropbox/mypy-PyCharm-plugin) - Mypy integration for PyCharm.
- [vim-mypy](https://github.com/Integralist/vim-mypy) - Mypy integration for Vim.
- [linter-mypy](https://atom.io/packages/linter-mypy) - Mypy integration for Atom.
- [emacs-flycheck-mypy](https://github.com/lbolla/emacs-flycheck-mypy) - Mypy integration for Emacs.


## Articles

### PEPs

- [PEP-483](https://www.python.org/dev/peps/pep-0483/) - About type hints theory.
- [PEP-484](https://www.python.org/dev/peps/pep-0484/) - About type annotations.
- [PEP-544](https://www.python.org/dev/peps/pep-0544/) - About protocols.
- [PEP-561](https://www.python.org/dev/peps/pep-0561/) - About distributing and packaging type information.
- [PEP-563](https://www.python.org/dev/peps/pep-0563/) - About postponed evaluation of annotations.
- [PEP-586](https://www.python.org/dev/peps/pep-0586/) - About literal types.
- [PEP-3107](https://www.python.org/dev/peps/pep-3107/) - About function annotations.

### Python docs

- [typing](https://docs.python.org/3/library/typing.html) - Support for type hints.

### Tools' docs

- [MyPy docs](https://mypy.readthedocs.io/en/latest/stubs.html) - General information about stubs.

### Third-party articles

- [1-minute guide to real constants in Python](https://sobolevn.me/2018/07/real-python-contants) - Full tutorial about `Final` constants and inheritance.
- [Simple dependent types in Python](https://sobolevn.me/2019/01/simple-dependent-types-in-python) - Full tutorial about `Literal` types.
- [Typechecking Django and DRF](https://sobolevn.me/2019/08/typechecking-django-and-drf) - Full tutorial about type-checking django.
- [Testing mypy stubs, plugins, and types](https://sobolevn.me/2019/08/testing-mypy-types) - Full tutorial about testing mypy types.
- [The state of type hints in Python](https://www.bernat.tech/the-state-of-type-hints-in-python/) - As of May 2018.

## Communities

- [python/typing](https://gitter.im/python/typing) - Official typing gitter chat.
- [TypedDjango](https://gitter.im/mypy-django/Lobby) - Official organisation gitter chat.
- [PythonRu#typing](https://python-ru.slack.com) - Russian slack chat (invites are [here](https://slack.python.ru/)) about types.


## Related

- [awesome-python](https://github.com/vinta/awesome-python) - Curated list of awesome Python frameworks, libraries, software and resources.
- [python-typecheckers](https://github.com/ethanhs/python-typecheckers) - List of Python type checkers: static and runtime.


## License

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
