steps:
- name: 'docker.io/library/python:3.7'
  id: UnitTest
  entrypoint: /bin/sh
  args:
  - -c
  - 'pip install pytest && pip install -r requirements.txt && pytest test/*_test.py'