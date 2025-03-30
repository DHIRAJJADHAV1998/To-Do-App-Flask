1 install migrate
  pip install flask-migrate
2 In your powershell run follwing commands to makemigrations
  python
  flask db init (only run at first time)
  flask db migrate -m "Initial migration"
  flask db upgrade
