# Awesome Python Typing [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![Gitter](https://img.shields.io/gitter/room/mypy-django/Lobby?color=9cf&style=flat-square)][TypedDjango]

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

[Full list of typed projects on PyPi](https://pypi.org/search/?q=&o=&c=Typing+%3A%3A+Typed) is here.


## Static type checkers

- [mypy](https://github.com/python/mypy) - Optional static typing for Python 3 and 2 (PEP 484).
- [pyre](https://pyre-check.org/) - Performant type-checker for Python 3.
- [pytype](https://github.com/google/pytype) - Tool to check and infer types for Python code - without requiring type annotations.
- [PyCharm](https://www.jetbrains.com/pycharm/) - IDE for Professional Developers.
- [pyright](https://github.com/Microsoft/pyright) - Fast type checker meant for large Python source bases. It can run in a “watch” mode and performs fast incremental updates when files are modified.
- [pyanalyze](https://github.com/quora/pyanalyze) - Extensible static analyzer and type checker for Python.

## Dynamic type checkers

- [beartype](https://github.com/beartype/beartype) - Unbearably fast `O(1)` runtime type-checking in pure Python.
- [pytypes](https://github.com/Stewori/pytypes) - Provides a rich set of utilities for runtime typechecking.
- [pydantic](https://github.com/samuelcolvin/pydantic) - Data parsing using Python type hinting. Supports dataclasses.
- [typeguard](https://github.com/agronholm/typeguard) - Another one runtime type checker.
- [typical](https://github.com/seandstewart/typical/) - Data parsing and automatic type-coercion using type hinting. Supports dataclasses, standard classes, function signatures, and more.

## Stub packages

- [Typeshed](https://github.com/python/typeshed) - Collection of library stubs for Python, with static types.
- [django-stubs](https://github.com/typeddjango/django-stubs) - Stubs for [Django](https://github.com/django/django).
- [djangorestframework-stubs](https://github.com/typeddjango/djangorestframework-stubs) - Stubs for [DRF](https://github.com/encode/django-rest-framework).
<!--lint disable double-link-->
- [dry-python/returns](https://github.com/dry-python/returns) - Stubs for [returns](https://github.com/dry-python/returns).
<!--lint enable double-link-->
- [sqlalchemy-stubs](https://github.com/dropbox/sqlalchemy-stubs) - Stubs for [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy).
- [grpc-stubs](https://github.com/shabbyrobe/grpc-stubs) - Stubs for [grpc](https://github.com/grpc/grpc).
- [boto3-stubs](https://github.com/vemel/mypy_boto3_builder) - Stubs for [boto3](https://github.com/boto/boto3).
- [botostubs](https://github.com/jeshan/botostubs) - Gives you code assistance for any boto3 API in any IDE.
- [PyQt5-stubs](https://github.com/stlehmann/PyQt5-stubs) - Stubs for [PyQt5](https://www.riverbankcomputing.com/software/pyqt/intro).
- [lxml-stubs](https://github.com/lxml/lxml-stubs) - Stubs for [lxml](https://lxml.de).
- [ordered-set-stubs](https://github.com/rominf/ordered-set-stubs) - Stubs for [OrderedSet](https://github.com/LuminosoInsight/ordered-set).
- [pyspark-stubs](https://github.com/zero323/pyspark-stubs) - Stubs for [PySpark](https://spark.apache.org/docs/latest/api/python/index.html).
- [pythonista-stubs](https://github.com/hbmartin/pythonista-stubs) - Stubs for [Pythonista](http://omz-software.com/pythonista/docs/ios/).
- [wsgitypes](https://github.com/shabbyrobe/wsgitypes) - Typing for WSGI application implementers. These are not stub files, they're interfaces you mark support for to help typecheck WSGI conformance.
- [data-science-types](https://github.com/predictive-analytics-lab/data-science-types) - Stubs for [NumPy], [pandas](https://github.com/pandas-dev/pandas), and [Matplotlib](https://github.com/matplotlib/matplotlib).

## Backports and improvements

- [typed-ast](https://github.com/python/typed_ast) - Modified fork of CPython's ast module that parses `# type:` comments.
- [typing-extensions](https://github.com/python/typing/tree/master/typing_extensions) - Backported and experimental type hints.
- [typingplus](https://github.com/contains-io/typingplus/) - Backport support, dynamic is_instance and cast for abstract types.
- [typet](https://github.com/contains-io/typet) - Length-bounded types, dynamic object validation.
- [typing_utils](https://github.com/bojiang/typing_utils) - Backport 3.8+ runtime typing utils(for eg: get_origin) & add issubtype & more.

## Tools

### Linters

- [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) - The strictest and most opinionated python linter ever.
- [flake8-mypy](https://github.com/ambv/flake8-mypy) - Plugin for flake8 integrating mypy.
- [flake8-pyi](https://github.com/ambv/flake8-pyi) - Plugin for Flake8 that provides specializations for type hinting stub files.
- [flake8-annotations-complexity](https://github.com/best-doctor/flake8-annotations-complexity) - Plugin for flake8 to validate annotations complexity.
- [flake8-annotations](https://github.com/sco1/flake8-annotations) - Plugin for flake8 to check for presence of type annotations in function definitions.
- [flake8-typing-imports](https://github.com/asottile/flake8-typing-imports) - Plugin which checks that typing imports are properly guarded.
- [flake8-typing-only-imports](https://github.com/sondrelg/flake8-typing-only-imports) - flake8 plugin that helps identify which imports to put into type-checking blocks, and how to adjust your type annotations once imports are moved.

### Testing

- [pytest-mypy](https://github.com/dbader/pytest-mypy) - Mypy static type checker plugin for Pytest.
- [pytest-mypy-plugins](https://github.com/typeddjango/pytest-mypy-plugins) - Pytest plugin for testing mypy types, stubs, and plugins.
- [pytest-mypy-testing](https://github.com/davidfritzsche/pytest-mypy-testing) - Pytest plugin to test mypy static type analysis.

### Working with types

- [merge_pyi](https://github.com/google/pytype/tree/master/pytype/tools/merge_pyi) - Part of pytype toolchain, applies stub files onto source code.
- [retype](https://github.com/ambv/retype) - Another tool to apply stubs to code.
- [mypy-protobuf](https://github.com/dropbox/mypy-protobuf) - Tool to generate mypy stubs from protobufs.
- [mypyc](https://github.com/python/mypy/tree/master/mypyc) - Compiles mypy-annotated, statically typed Python modules into CPython C extensions.
- [typing_inspect](https://github.com/ilevkivskyi/typing_inspect) - The typing_inspect module defines experimental API for runtime inspection of types defined in the Python standard typing module.
- [typing-json](https://pypi.org/project/typing-json/) - Lib for working with typed objects and JSON.
- [com2ann](https://github.com/ilevkivskyi/com2ann) - Tool for translation of type comments to type annotations in Python.
- [mypy-silent](https://github.com/whtsky/mypy-silent/) - Silence mypy by adding or removing code comments. 

### Helper tools to add annotations to existing code

- [MonkeyType](https://github.com/instagram/MonkeyType) - Collects runtime types of function arguments and return values, and can automatically generate stub files or even add draft type annotations directly to your Python code based on the types collected at runtime.
- [pytest-monkeytype](https://github.com/mariusvniekerk/pytest-monkeytype) - MonkeyType plugin for pytest.
- [pyannotate](https://github.com/dropbox/pyannotate) - Insert annotations into your source code based on call arguments and return types observed at runtime.
- [pytest-annotate](https://github.com/kensho-technologies/pytest-annotate) - Pyannotate plugin for pytest.
<!--lint disable double-link-->
- [pyre infer](https://github.com/facebook/pyre-check) - Pyre has a powerful feature for migrating codebases to a typed format. The [infer](https://pyre-check.org/docs/pysa-coverage/) command-line option ingests a file or directory, makes educated guesses about the types used, and applies the annotations to the files.
<!--lint enable double-link-->
- [pytype annotate-ast](https://github.com/google/pytype/tree/master/pytype/tools/annotate_ast) - A work-in-progress tool to annotate the nodes of an AST with their Python types.
- [Typilus](https://github.com/typilus/typilus) - A deep learning algorithm for predicting types in Python. Also available as a [GitHub action](https://github.com/typilus/typilus-action)
- [Type4Py](https://github.com/saltudelft/type4py) - Deep Similarity Learning-Based Type Inference for Python.


### Mypy plugins

- [pynamodb-mypy](https://github.com/pynamodb/pynamodb-mypy) - Plugin for [PynamoDB](https://github.com/pynamodb/PynamoDB) support.
- [mypy-zope](https://github.com/Shoobx/mypy-zope) - Plugin for [zope.interface](https://zopeinterface.readthedocs.io/en/latest/) support.
- [mypy/plugins](https://github.com/python/mypy/tree/master/mypy/plugins) - Plugins already integrated into mypy.
- [loguru-mypy](https://github.com/kornicameister/loguru-mypy) - Plugin for [loguru](https://github.com/Delgan/loguru) support.


## Integrations

- [mypy-PyCharm-plugin](https://github.com/dropbox/mypy-PyCharm-plugin) - Mypy integration for PyCharm.
- [vim-mypy](https://github.com/Integralist/vim-mypy) - Mypy integration for Vim.
- [linter-mypy](https://atom.io/packages/linter-mypy) - Mypy integration for Atom.
- [emacs-flycheck-mypy](https://github.com/lbolla/emacs-flycheck-mypy) - Mypy integration for Emacs.


## Articles

### PEPs

- [PEP-3107](https://www.python.org/dev/peps/pep-3107) - Function Annotations.
- [PEP-482](https://www.python.org/dev/peps/pep-0482/) - Literature Overview for Type Hints.
- [PEP-483](https://www.python.org/dev/peps/pep-0483/) - The Theory of Type Hints.
- [PEP-484](https://www.python.org/dev/peps/pep-0484/) - Type Hints.
- [PEP-526](https://www.python.org/dev/peps/pep-0526/) - Syntax for Variable Annotations.
- [PEP-544](https://www.python.org/dev/peps/pep-0544/) - Protocols: Structural subtyping (static duck typing).
- [PEP-557](https://www.python.org/dev/peps/pep-0557/) - Data Classes.
- [PEP-560](https://www.python.org/dev/peps/pep-0560/) - Core support for typing module and generic types.
- [PEP-561](https://www.python.org/dev/peps/pep-0561/) - Distributing and Packaging Type Information.
- [PEP-563](https://www.python.org/dev/peps/pep-0563/) - Postponed Evaluation of Annotations.
- [PEP-585](https://www.python.org/dev/peps/pep-0585/) - Type Hinting Generics In Standard Collections.
- [PEP-586](https://www.python.org/dev/peps/pep-0586/) - Literal Types.
- [PEP-589](https://www.python.org/dev/peps/pep-0589/) - TypedDict: Type Hints for Dictionaries with a Fixed Set of Keys.
- [PEP-591](https://www.python.org/dev/peps/pep-0591/) - Adding a final qualifier to typing.
- [PEP-593](https://www.python.org/dev/peps/pep-0593/) - Flexible function and variable annotations.
- [PEP-604](https://www.python.org/dev/peps/pep-0604/) - Complementary syntax for Union[].
- [PEP-612](https://www.python.org/dev/peps/pep-0612/) - Parameter Specification Variables.
- [PEP-613](https://www.python.org/dev/peps/pep-0613/) - Explicit Type Aliases.


### Python docs

- [typing](https://docs.python.org/3/library/typing.html) - Support for type hints.

### Tools' docs

- [MyPy docs](https://mypy.readthedocs.io/en/latest/stubs.html) - General information about stubs.

### Third-party articles

- [1-minute guide to real constants in Python](https://sobolevn.me/2018/07/real-python-contants) - Full tutorial about `Final` constants and inheritance.
- [Simple dependent types in Python](https://sobolevn.me/2019/01/simple-dependent-types-in-python) - Full tutorial about `Literal` types.
- [Typechecking Django and DRF](https://sobolevn.me/2019/08/typechecking-django-and-drf) - Full tutorial about type-checking django.
- [Testing mypy stubs, plugins, and types](https://sobolevn.me/2019/08/testing-mypy-types) - Full tutorial about testing mypy types.
- [The state of type hints in Python](https://bernat.tech/posts/the-state-of-type-hints-in-python/) - As of May 2018.
- [PyTest MonkeyType Introduction](https://dev.to/ldrscke/type-annotate-an-existing-python-django-codebase-with-monkeytype-254i) - Type Annotate an existing Python Django Codebase with MonkeyType.

## Communities

- [python/typing](https://gitter.im/python/typing) - Official typing gitter chat.
<!--lint disable awesome-list-item-->
- [TypedDjango] - Official organisation gitter chat.
<!--lint enable awesome-list-item-->
- [PythonRu#typing](https://python-ru.slack.com) - Russian slack chat (invites are [here](https://slack.python.ru/)) about types.


## Related

- [awesome-python](https://github.com/vinta/awesome-python) - Curated list of awesome Python frameworks, libraries, software and resources.
- [python-typecheckers](https://github.com/ethanhs/python-typecheckers) - List of Python type checkers: static and runtime.


[typeddjango]: https://gitter.im/mypy-django/Lobby
[numpy]: http://github.com/numpy/numpy
