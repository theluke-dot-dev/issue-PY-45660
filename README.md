Tested with Poetry 1.1.4 or newer:

```sh
git clone [...]
poetry install
cd ./issue-PY-45660/py_45560
celery -A py_45660.apps.temp worker
```

The command succeeds to run with found configuration (besides the missing celery backend error).
