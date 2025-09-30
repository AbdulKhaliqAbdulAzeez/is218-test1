# How to run lint/tests

1. pip install -r requirements.txt
2. pylint --errors-only src
3. pytest tests -v
4. pytest --pylint src -v
