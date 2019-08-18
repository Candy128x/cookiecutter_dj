# Commands
	
---
- description..
- => pwd


---
- Create a virtualenv for your project and activate it:

- => mkvirtualenv <virtualenv name>
- => workon <virtualenv name>


---
- => pip3 install django


---
- => pip install cookiecutter
- op:
```
(venv) ashish@ashish-Vostro-3478:cookiecutter_dj$ pip install cookiecutter

Collecting cookiecutter
  Downloading https://files.pythonhosted.org/packages/16/99/1ca3a75978270288354f419e9166666801cf7e7d8df984de44a7d5d8b8d0/cookiecutter-1.6.0-py2.py3-none-any.whl (50kB)
    100% |████████████████████████████████| 51kB 594kB/s 
Collecting jinja2>=2.7 (from cookiecutter)
  Using cached https://files.pythonhosted.org/packages/1d/e7/fd8b501e7a6dfe492a433deb7b9d833d39ca74916fa8bc63dd1a4947a671/Jinja2-2.10.1-py2.py3-none-any.whl
Collecting poyo>=0.1.0 (from cookiecutter)
  Downloading https://files.pythonhosted.org/packages/42/50/0b0820601bde2eda403f47b9a4a1f270098ed0dd4c00c443d883164bdccc/poyo-0.5.0-py2.py3-none-any.whl
Collecting binaryornot>=0.2.0 (from cookiecutter)
  Downloading https://files.pythonhosted.org/packages/24/7e/f7b6f453e6481d1e233540262ccbfcf89adcd43606f44a028d7f5fae5eb2/binaryornot-0.4.4-py2.py3-none-any.whl
Collecting click>=5.0 (from cookiecutter)
  Using cached https://files.pythonhosted.org/packages/fa/37/45185cb5abbc30d7257104c434fe0b07e5a195a6847506c074527aa599ec/Click-7.0-py2.py3-none-any.whl
Collecting future>=0.15.2 (from cookiecutter)
  Downloading https://files.pythonhosted.org/packages/90/52/e20466b85000a181e1e144fd8305caf2cf475e2f9674e797b222f8105f5f/future-0.17.1.tar.gz (829kB)
    100% |████████████████████████████████| 829kB 754kB/s 
Collecting requests>=2.18.0 (from cookiecutter)
  Using cached https://files.pythonhosted.org/packages/51/bd/23c926cd341ea6b7dd0b2a00aba99ae0f828be89d72b2190f27c11d4b7fb/requests-2.22.0-py2.py3-none-any.whl
Collecting jinja2-time>=0.1.0 (from cookiecutter)
  Downloading https://files.pythonhosted.org/packages/6a/a1/d44fa38306ffa34a7e1af09632b158e13ec89670ce491f8a15af3ebcb4e4/jinja2_time-0.2.0-py2.py3-none-any.whl
Collecting whichcraft>=0.4.0 (from cookiecutter)
  Downloading https://files.pythonhosted.org/packages/19/31/b35bfa8bd4a5b539a4a1cef56f0701c93387b9a644572bf2d31440351324/whichcraft-0.6.0-py2.py3-none-any.whl
Collecting MarkupSafe>=0.23 (from jinja2>=2.7->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/6e/57/d40124076756c19ff2269678de7ae25a14ebbb3f6314eb5ce9477f191350/MarkupSafe-1.1.1-cp35-cp35m-manylinux1_x86_64.whl
Collecting chardet>=3.0.2 (from binaryornot>=0.2.0->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/bc/a9/01ffebfb562e4274b6487b4bb1ddec7ca55ec7510b22e4c51f14098443b8/chardet-3.0.4-py2.py3-none-any.whl
Collecting idna<2.9,>=2.5 (from requests>=2.18.0->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/14/2c/cd551d81dbe15200be1cf41cd03869a46fe7226e7450af7a6545bfc474c9/idna-2.8-py2.py3-none-any.whl
Collecting urllib3!=1.25.0,!=1.25.1,<1.26,>=1.21.1 (from requests>=2.18.0->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/e6/60/247f23a7121ae632d62811ba7f273d0e58972d75e58a94d329d51550a47d/urllib3-1.25.3-py2.py3-none-any.whl
Collecting certifi>=2017.4.17 (from requests>=2.18.0->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/69/1b/b853c7a9d4f6a6d00749e94eb6f3a041e342a885b87340b79c1ef73e3a78/certifi-2019.6.16-py2.py3-none-any.whl
Collecting arrow (from jinja2-time>=0.1.0->cookiecutter)
  Downloading https://files.pythonhosted.org/packages/4f/c6/32df2c68e02e2d6b4457223fa499634edabb2d4ff74f00087ffff49b4be4/arrow-0.14.5-py2.py3-none-any.whl
Collecting python-dateutil (from arrow->jinja2-time>=0.1.0->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/41/17/c62faccbfbd163c7f57f3844689e3a78bae1f403648a6afb1d0866d87fbb/python_dateutil-2.8.0-py2.py3-none-any.whl
Collecting six>=1.5 (from python-dateutil->arrow->jinja2-time>=0.1.0->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/73/fb/00a976f728d0d1fecfe898238ce23f502a721c0ac0ecfedb80e0d88c64e9/six-1.12.0-py2.py3-none-any.whl
Installing collected packages: MarkupSafe, jinja2, poyo, chardet, binaryornot, click, future, idna, urllib3, certifi, requests, six, python-dateutil, arrow, jinja2-time, whichcraft, cookiecutter
  Running setup.py install for future ... done
Successfully installed MarkupSafe-1.1.1 arrow-0.14.5 binaryornot-0.4.4 certifi-2019.6.16 chardet-3.0.4 click-7.0 cookiecutter-1.6.0 future-0.17.1 idna-2.8 jinja2-2.10.1 jinja2-time-0.2.0 poyo-0.5.0 python-dateutil-2.8.0 requests-2.22.0 six-1.12.0 urllib3-1.25.3 whichcraft-0.6.0
```


- => cookiecutter https://github.com/pydanny/cookiecutter-django.git
- op:
```
(venv) ashish@ashish-Vostro-3478:cookiecutter_dj$ cookiecutter https://github.com/pydanny/cookiecutter-django.git

project_name [My Awesome Project]: cookiecutter_demo  
project_slug [cookiecutter_demo]: cookiecutter_app
description [Behold My Awesome Project!]: demo app
author_name [Daniel Roy Greenfeld]: Ashish
domain_name [example.com]: 
email [ashish@example.com]: 
version [0.1.0]: 
Select open_source_license:
1 - MIT
2 - BSD
3 - GPLv3
4 - Apache Software License 2.0
5 - Not open source
Choose from 1, 2, 3, 4, 5 (1, 2, 3, 4, 5) [1]: 5
timezone [UTC]: 
windows [n]: 
use_pycharm [n]: 
use_docker [n]: 
Select postgresql_version:
1 - 11.3
2 - 10.8
3 - 9.6
4 - 9.5
5 - 9.4
Choose from 1, 2, 3, 4, 5 (1, 2, 3, 4, 5) [1]: 1
Select js_task_runner:
1 - None
2 - Gulp
Choose from 1, 2 (1, 2) [1]: 1
Select cloud_provider:
1 - AWS
2 - GCP
3 - None
Choose from 1, 2, 3 (1, 2, 3) [1]: 3
custom_bootstrap_compilation [n]: y
use_compressor [n]: 
use_celery [n]: 
use_mailhog [n]: 
use_sentry [n]: 
use_whitenoise [n]: 
use_heroku [n]: 
use_travisci [n]: 
keep_local_envs_in_vcs [y]: n
debug [n]: 
 [WARNING]: You chose not to use a cloud provider, media files won't be served in production.
 [SUCCESS]: Project initialized, keep up the good work!
```


---
- => pip install -r requirements/local.txt

- op:
```
(venv) ashish@ashish-Vostro-3478:cookiecutter_app$ pip install -r requirements/local.txt
Collecting pytz==2019.2 (from -r requirements/./base.txt (line 1))
  Using cached https://files.pythonhosted.org/packages/87/76/46d697698a143e05f77bec5a526bf4e56a0be61d63425b68f4ba553b51f2/pytz-2019.2-py2.py3-none-any.whl
Collecting python-slugify==3.0.3 (from -r requirements/./base.txt (line 2))
  Downloading https://files.pythonhosted.org/packages/a2/5d/bd30413c00bbed3945558aca07c55944073e1e30abeee1f06515281f9811/python-slugify-3.0.3.tar.gz
Collecting Pillow==6.1.0 (from -r requirements/./base.txt (line 3))
  Using cached https://files.pythonhosted.org/packages/d6/98/0d360dbc087933679398d73187a503533ec0547ba4ffd2115365605559cc/Pillow-6.1.0-cp35-cp35m-manylinux1_x86_64.whl
Collecting argon2-cffi==19.1.0 (from -r requirements/./base.txt (line 4))
  Downloading https://files.pythonhosted.org/packages/1e/14/d7fe69cb4efad2926f85d0ec4736f29fbb6995e2a5bf5501b3cd0173d32b/argon2_cffi-19.1.0-cp34-abi3-manylinux1_x86_64.whl (93kB)
    100% |████████████████████████████████| 102kB 895kB/s 
Collecting redis==3.3.7 (from -r requirements/./base.txt (line 5))
  Downloading https://files.pythonhosted.org/packages/a1/ec/cff42507ef8efe9c63bb454bae7ac70af8706f584ecc96b5a23ca6499e1a/redis-3.3.7-py2.py3-none-any.whl (66kB)
    100% |████████████████████████████████| 71kB 1.1MB/s 
Collecting django==2.2.4 (from -r requirements/./base.txt (line 9))
  Using cached https://files.pythonhosted.org/packages/d6/57/66997ca6ef17d2d0f0ebcd860bc6778095ffee04077ca8985928175da358/Django-2.2.4-py3-none-any.whl
Collecting django-environ==0.4.5 (from -r requirements/./base.txt (line 10))
  Downloading https://files.pythonhosted.org/packages/9f/32/76295a1a5d00bf556c495216581c6997e7fa5f533b2229e0a9d6cbaa95ae/django_environ-0.4.5-py2.py3-none-any.whl
Collecting django-model-utils==3.2.0 (from -r requirements/./base.txt (line 11))
  Downloading https://files.pythonhosted.org/packages/7e/ed/c8d4654bce5859766c989ca0cc3dc439d3abd00f5b1c6ef4d80b0a5f2871/django_model_utils-3.2.0-py2.py3-none-any.whl
Collecting django-allauth==0.39.1 (from -r requirements/./base.txt (line 12))
  Downloading https://files.pythonhosted.org/packages/9c/dc/b7821e2b62311e402c24749f32dcbc337501f1d87e4eb2d4ef19e1e95f31/django-allauth-0.39.1.tar.gz (534kB)
    100% |████████████████████████████████| 542kB 1.8MB/s 
Collecting django-crispy-forms==1.7.2 (from -r requirements/./base.txt (line 13))
  Downloading https://files.pythonhosted.org/packages/9a/05/6bad05742d185ec2fabfa4deab05cafde286eb3f383fba24b3674340aca2/django_crispy_forms-1.7.2-py2.py3-none-any.whl (105kB)
    100% |████████████████████████████████| 112kB 3.7MB/s 
Collecting django-redis==4.10.0 (from -r requirements/./base.txt (line 14))
  Downloading https://files.pythonhosted.org/packages/f8/79/1fd48c585d5a95fd314571ac34c13f6bc1f7e65cbb5ed9ac0299212f35ce/django_redis-4.10.0-py2.py3-none-any.whl
Collecting djangorestframework==3.10.2 (from -r requirements/./base.txt (line 17))
  Using cached https://files.pythonhosted.org/packages/af/2a/055e65e1aa25cc2726d68d78b859a7b5955c673bc5e4646b205c21e05b25/djangorestframework-3.10.2-py3-none-any.whl
Collecting coreapi==2.3.3 (from -r requirements/./base.txt (line 18))
  Downloading https://files.pythonhosted.org/packages/fc/3a/9dedaad22962770edd334222f2b3c3e7ad5e1c8cab1d6a7992c30329e2e5/coreapi-2.3.3-py2.py3-none-any.whl
Collecting Werkzeug==0.14.1 (from -r requirements/local.txt (line 3))
  Downloading https://files.pythonhosted.org/packages/20/c4/12e3e56473e52375aa29c4764e70d1b8f3efa6682bef8d0aae04fe335243/Werkzeug-0.14.1-py2.py3-none-any.whl (322kB)
    100% |████████████████████████████████| 327kB 2.1MB/s 
Collecting ipdb==0.12.2 (from -r requirements/local.txt (line 4))
  Downloading https://files.pythonhosted.org/packages/df/78/3d0d7253dc85549db182cbe4b43b30c506c84008fcd39898122c9b6306a9/ipdb-0.12.2.tar.gz
Collecting Sphinx==2.1.2 (from -r requirements/local.txt (line 5))
  Downloading https://files.pythonhosted.org/packages/6e/e5/c9ba68935cd2d72c553d49bc156bfb15ddb40e734ea7e3f238d8bd6ca6f1/Sphinx-2.1.2-py3-none-any.whl (3.2MB)
    100% |████████████████████████████████| 3.3MB 5.0MB/s 
Collecting psycopg2-binary==2.8.3 (from -r requirements/local.txt (line 6))
  Downloading https://files.pythonhosted.org/packages/73/a4/97f13ca6a21865a1c9b3c5d3838c3ea574267dc675a698610418b1b8704e/psycopg2_binary-2.8.3-cp35-cp35m-manylinux1_x86_64.whl (2.9MB)
    100% |████████████████████████████████| 2.9MB 2.6MB/s 
Collecting mypy==0.720 (from -r requirements/local.txt (line 10))
  Downloading https://files.pythonhosted.org/packages/ee/e9/b9e8be2e4ceb55ef5ada5eb6fb8fccb6a0bc00cc5df5f8534ce8e682db8b/mypy-0.720-cp35-cp35m-manylinux1_x86_64.whl (20.7MB)
    100% |████████████████████████████████| 20.7MB 532kB/s 
Collecting pytest==5.1.0 (from -r requirements/local.txt (line 11))
  Downloading https://files.pythonhosted.org/packages/2b/65/9f1c6797b6acaff47f818312c6335a34e9919beaf123b72e0069490f2422/pytest-5.1.0-py3-none-any.whl (223kB)
    100% |████████████████████████████████| 225kB 1.5MB/s 
Collecting pytest-sugar==0.9.2 (from -r requirements/local.txt (line 12))
  Downloading https://files.pythonhosted.org/packages/da/3b/f1e3c8830860c1df8f0e0f6713932475141210cfa021e362ca2774d2bf02/pytest_sugar-0.9.2-py2.py3-none-any.whl
Collecting flake8==3.7.8 (from -r requirements/local.txt (line 16))
  Downloading https://files.pythonhosted.org/packages/26/de/3f815a99d86eb10464ea7bd6059c0172c7ca97d4bdcfca41051b388a653b/flake8-3.7.8-py2.py3-none-any.whl (70kB)
    100% |████████████████████████████████| 71kB 1.2MB/s 
Collecting coverage==4.5.4 (from -r requirements/local.txt (line 17))
  Downloading https://files.pythonhosted.org/packages/99/fc/7c7fa3a7764c374fde2fb29f9b4f906e8c4fdb643fad5511d351fcc3853d/coverage-4.5.4-cp35-cp35m-manylinux1_x86_64.whl (205kB)
    100% |████████████████████████████████| 215kB 1.4MB/s 
Collecting black==19.3b0 (from -r requirements/local.txt (line 18))
  Could not find a version that satisfies the requirement black==19.3b0 (from -r requirements/local.txt (line 18)) (from versions: )
No matching distribution found for black==19.3b0 (from -r requirements/local.txt (line 18))

```

---
- => pip install -r requirements/base.txt
- => pip install django-debug-toolbar
- => pip install django-extensions

- => sudo apt-get install build-dep python-psycopg2
- => pip install psycopg2 

- => python3 manage.py migrate