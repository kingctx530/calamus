# Quick start

* Environment require
	* gettext-tools-0.17
	* gettext-runtime-0.17-1
	* Manjaro 22.0
	* Python 3.11
	* Django 4.2

* Installation (clone to your Django project)
```python
git clone https://github.com/kingctx530/calamus.git
```

* Add `calamus` to your INSTALLED_APPS setting like this:
```python
INSTALLED_APPS = [
	...
	'calamus',
]
```


* How can use
```python
python manage.py newapp `app name`
```

# Soft action
1. Auto register to INSTALLED_APPS.
2. Auto modify the app format to i18n.
3. Auto generate `urls.py` to the app.
4. Auto generate `templates` folder to the app.
5. Auto generate `forms.py` to the app.