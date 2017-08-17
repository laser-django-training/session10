**Read Me First**
- Copy `nginx-configuration` file to `/etc/nginx/sites-available/session7`
- Make a soft link of this file in `/etc/nginx/sites-enabled`
- Copy `gunicorn-configuration.service` to `/lib/systemd/system/gunicorn-session7.service`
- Copy `settings.py` to the file with the same name inside your django project 
- Type in terminal: `sudo systemctl restart nginx gunicorn-session7`

**Note**
Don't forget to install nginx, mysql, django and the other packages before you start.

