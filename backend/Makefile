pip:
	pip install -r requirements.txt

mig:
	python manage.py makemigrations users statistic twofa chat pong
	python manage.py migrate

suser:
	python manage.py createsuperuser

make truffle:
	cd blchain/truffle && truffle migrate --network development

run:
	python manage.py runserver 0.0.0.0:8000