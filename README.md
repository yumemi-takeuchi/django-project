# mysite スケルトン

## quick start
```
git clone git@github.com:yumemi-takeuchi/django-project.git
cd docker
cp .env-example .env 
docker-compose up -d
```

access:
http://localhost:9001/

## db migrations
```
docker-compose run app ./manage.py makemigrations
docker-compose run app ./manage.py migrate
```
## css 適用
```
docker-compose run app ./manage.py collectstatic
```
### TODO
- チュートリアル Pollsアプリケーションの作成
https://docs.djangoproject.com/ja/2.2/intro/tutorial01/#creating-the-polls-app
