# deploy-tool

The aim of this tool is to automate some the deployment process of laravel apps.

## TODO
- [x] Mechanisim to connect over ssh to server
- [ ] Check if server has been provisioned
- [ ] Run a provision script if need be
- [ ] Create a project folder (/var/project/project_name)
- [ ] initilize it at a bare repo
- [ ] craete post recieve scripts and make them executable (chmod +x)
    - responsible for composer install, migrations, etc
    - clean up
    - restart services
- [ ] add new git remotoe to the local repo and push
- [ ] create nginx or caddy file (/etc/nginx/sites-enabled/hostname.com)
- [ ] restart services

## Components needed
1. Some templating engine for creating bash/nginx/caddy files
2. ...
