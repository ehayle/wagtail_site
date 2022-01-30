# wagtailTemplate
Startup Notes:
$mkdir 'projectname'
$cd 'projectname'
*new virtual environment
$virtualenv -p python3
$source env/bin/activate

$git clone 'DirectoryName'
$cd 'projectname'

$pip install -r requirements.txt
*check for installations
$pip show wagtail
$pip show django

$./manage.py runserver
*shows unapplied migrations
*cancel server
$./manage.py makemigrations
$./manage.py migrate
$./manage.py runserver