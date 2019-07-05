# django-social-auth
Google, Facebook, Twitter, GitHubを使用したSocialログインのサンプル
https://nmomos.com/2019/07/05/django-social-auth/

# 実行方法
リポジトリのクローン
```bash
https://github.com/mila411/django-social-auth.git
```
パッケージのインストール
```bash
pip install -r requirements.txt
```

各SNS毎のID・Secretをsettings.pyへ記述

マイグレート
```bash
python manage.py migrate
```
開発サーバ起動
```bash
python manage.py runserver
```
※Facebookのみ
```basu
HTTPS=on python manage.py runserver
```
