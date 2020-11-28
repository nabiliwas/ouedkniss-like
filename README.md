
# ouedkniss like
ouedkniss like is a django project that allow users to create announces and search among them 


## features
- full authentication system (session based) 
- announces crud operations
- comment system with JQuery 

## INSTALLED APPS 

```python
INSTALLED_APPS = [
    'accounts.apps.AccountsConfig', # authentication app
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'crispy_forms',
    'rest_framework',
    'rest_framework.authtoken',
    'drf_yasg',
    'taggit',
    'announce.apps.AnnounceConfig', # our main app
]
```


