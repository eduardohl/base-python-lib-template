====
How To's
====

poetry
----
* To run::

    poetry init
    poetry new <module name>
    poetry update
    poetry install
    poetry shell
    poetry add <library>
    poetry build
    poetry publish

cdk
----
* To run::

    cdk init
    cdk ls
    cdk synth
    cdk deploy
    cdk diff

cdk_nag
----
* In Code::

    from aws_cdk import core
    import cdk_nag
    core.Aspects.of(app).add(cdk_nag.AwsSolutionsChecks())

* To run::

    cdk synth

pre-commit
----
* In Code::

    from aws_cdk import core
    import cdk_nag
    core.Aspects.of(app).add(cdk_nag.AwsSolutionsChecks())

* To run::

    pre-commit install
    pre-commit run --all-files

suggestions
----
* libraries
    * datetime: arrow and pendulum
    * pydantic: runtime type validation
    * interrogate: ensure docstrings
    * commitizen: for commits

* suggested techniques
    * asyncio stdlib: for concurrency
    * contextlib: for "with" methods
    * logging stdlib: for logging

* useful annotations
    * lru_cache: for memoizing results
    * datatype: for data objects

* pycharm plugins
    * awstoolkit
    * gittoolbox

* for aws
    * boto3
    * cdk
    * cdk-nag
    * moto
