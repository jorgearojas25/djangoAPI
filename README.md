A base django api
=============

for run this project run

1. build images:'docker-compose -f local.yml build'
2. see with: 'docker images'
3. run stack: 'docker-compose -f local.yml up'
4. administration commands: 'docker-compose -f local.yml run --rm django python manage.py createsuperuser'

To see de contaniers: 'docker-compose -f local.yml ps'

finish with: 'docker-compose -f local.yml down'

debbuging comands: first kill django 
    'docker rm -f djangoapi_django_1'
    'docker-compose -f local.yml run --rm --service-ports django'




