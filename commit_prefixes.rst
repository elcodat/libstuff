Suggested (git) commit message prefixes. Inspired by `scipy's docs <scipy_>`_.

ENH Enhancement
    Add a new feature (function, method, class, module), but also stuff like
    substantial speed improvements or refactoring work.

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
    World-facing release-related changes (setup.py, versions, pip, packaging,
    dependencies).

BLD Build system
    Internal build-related (setup.py, compilers, extensions).

MNT Maintenance
    This is the new preferred replacement for INT ("internal change"). Any
    internal change such as refactoring, style or cleanup that is neither API
    nor BEH.

STY Style change
    pep8-ish style fixes. Use this or MNT.

INT Internal change
    Deprecated, use MNT.

.. _scipy: https://docs.scipy.org/doc/numpy/dev/gitwash/development_workflow.html
