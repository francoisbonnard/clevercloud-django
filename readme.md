# readme

## first commit
Create readme.md file and make first commit

``` bash
git remote add clever git+ssh://git@push-n3-par-clevercloud-customers.services.clever-cloud.com/app_242bd1af-b099-4652-b690-cbe085b47c94.git

git branch -M master
git push -u clever master
# git push -u clever branch:master if you want to push a specific branch
```

github

``` bash
git branch -M main
git remote add origin https://github.com/francoisbonnard/clevercloud-django.git
git push -u origin main
```

![alt text](./img_readme/image6.png)

## second commit

create requirements.txt

    Django==5.0.3

second commit

Warning in the log

    You need to name a python module to use. Please set the CC_PYTHON_MODULE environment variable

Exemple in [github](https://github.com/CleverCloud/django-example/blob/master/clevercloud/python.json)

``` json
{
    "build": {
        "cache_dependancies": true
    },
    "deploy": {
        "module": "common.wsgi:application",
        "managetasks": [
            "collectstatic --noinput"
        ]
    }
}
```

![alt text](./img_readme/image.png)

## Commit 03

create basic app

    django-admin startproject photoshare
    cd photoshare
    python manage.py startapp  photos

add photos.apps.PhotosConfig in settings.py/installed_apps

in photos directory create templates/photos/gallery.html and updating views.py & 

Result of git push

![alt text](./img_readme/image2.png)

I have forgotten to update the env variables

New Build


![alt text](./img_readme/image4.png)
![alt text](./img_readme/image3.png)

change : 
common.wsgi:application with photoshare.photoshare.wsgi:application

![alt text](./img_readme/image5.png)

## commit 04

update wsgy.py

    os.environ.setdefault('DJANGO_SETTINGS_MODULE', 'photoshare.photoshare.settings')

## commit 05

change in settings.py 

    BASE_DIR = Path(__file__).resolve().parent.parent

by

    BASE_DIR = Path(__file__).resolve().parent

not working

## commit 06 


debug


    BASE_DIR = Path(__file__).resolve().parent.parent
    print(BASE_DIR)
    /home/bas/app_242bd1af-b099-4652-b690-cbe085b47c94/photoshare

See logs.md : Can't find the app "photo" in settings.py

## commit 07

settings.py photos.apps.PhotosConfig -> photoshare.photos.apps.PhotosConfig

## new key creative
