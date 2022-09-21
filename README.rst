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


toadd
----
* https://python-semantic-release.readthedocs.io/en/latest/
* https://pypi.org/project/commitizen/
* https://github.com/PyCQA/autoflake
* future / concurrency
* datetime
* check latest version of dependencies
* contextlib (for "with" methods)
* logging
* cache
* bolton/cython
* interrogate