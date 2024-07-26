# Django

1. 프로젝트 생성

django-admin startproject {pjt 프로젝트명}. 

2. 가상환경 생성

python -m venv venv

3. 가상환경 활성화

source venv/Script/activate

4. 가상환경 내부에 django 설치

pip install django

5. 서버 실행 (종료 단축키: 'ctrl + c')

python manage.py runserver

6. 앱 생성

django-admin startapp {app의 이름}

7. 앱 등록

python

INSTALLED_APPS = [
    ...
    '{app_name}'
]