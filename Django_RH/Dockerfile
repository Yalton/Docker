#465 Hello_World (Dockerfile)
FROM python:3

WORKDIR /mnt/nas/shared/Network/Mainframe/rabbithole_site/django_root:/usr/src/app

RUN pip install django

CMD [ "python", "./manage.py",  "runserver",  "0.0.0.0:8000"]
