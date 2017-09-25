# django
python manifest
include MANIFEST.in
include package.json
include *.rst
recursive-include django *
graft django
prune django/contrib/admin/bin
recursive-include docs *
recursive-include extras *
recursive-include js_tests *
recursive-include scripts *
recursive-include tests *
recursive-exclude * __pycache__
recursive-exclude * *.py[co]
graft docs
graft extras
graft js_tests
graft scripts
graft tests
global-exclude __pycache__
global-exclude *.py[co]
