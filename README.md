# cms_tutorial
Introduction to DJango CMS

# Setup
mkvirtualenv cms_tutorial
git clone https://github.com/hughy603/cms_tutorial
cd cms_tutorial
pip install django-cms

# Setup Postgres
sudo -u postgres createuser -D -A -P cms_tutorial
sudo -u postgres createdb -O cms_tutorial cms_tutorial
