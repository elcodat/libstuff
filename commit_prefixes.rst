Suggested (git) commit message prefixes. Inspired by `numpy's dev docs <numpy_>`_.

ENH Enhancement
    Add a new feature (function, method, class, module) that doesn't break the
    existing API. Also non-API improvements like substantial speed gains.

BUG Bug Fix
    Changes that fix a bug, but don't break APIs.

DOC Documentation changes
    Written docs or doc strings.

TST tests
    All things related to tests.

API API change
    User-facing API change (rm function/method/module/class, change call
    signature or important defaults). In general things that may break user
    code.

BEH Behavioral change a.k.a. "soft" API change
    Changes that are not API changes (e.g. add a warning, add a side effect
    like writing a file, change less important defaults such as compiler
    optimization flags). Things that won't break user code.

REL Release-related
    World-facing release-related changes (setup.py, versions, packaging,
    new or removed dependencies).

BLD Build system
    Internal build-related changes (setup.py, compilers, extensions, code
    checkers and linters).

MNT Maintenance
    Any internal change such as refactoring, style or cleanup that is neither API
    nor BEH.

STY Style change
    pep8-ish style fixes. Use this or MNT.

.. _numpy: https://numpy.org/devdocs/dev/development_workflow.html#writing-the-commit-message
