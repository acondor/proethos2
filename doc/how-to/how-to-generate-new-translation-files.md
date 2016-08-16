How to generate new translation files
=====================================

Execute this command for __pt_BR__:

```
php app/console translation:extract pt_BR --dir=./src/ --output-dir=./app/Resources/translations
```
Execute this command for __es_ES__:

```
php app/console translation:extract es_ES --dir=./src/ --output-dir=./app/Resources/translations
```
Execute this command for __fr_FR__:

```
php app/console translation:extract fr_FR --dir=./src/ --output-dir=./app/Resources/translations
```

Then, commit the updated files.