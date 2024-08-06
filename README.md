<<<<<<< HEAD
# angular-social-network
=======
# AngularSocialNetwork

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.0.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
>>>>>>> master

# Deployment Commands 

node version :- v18.17.0
angular version :- 


npm install
npm install -g @angular/cli@14.0.2

```

sudo fallocate -l 2G /swapfile
sudo chmod 600 /swapfile
sudo mkswap /swapfile
sudo swapon /swapfile
sudo swapon --show
df -h
cd angular-social-network/
ng serve --live-reload false
node --max_old_space_size=2048 node_modules/@angular/cli/bin/ng build --source-map=false
node --max_old_space_size=2048 node_modules/@angular/cli/bin/ng serve --host 0.0.0.0 --live-reload false
node --max_old_space_size=2048 node_modules/@angular/cli/bin/ng build
node --max_old_space_size=2048 node_modules/@angular/cli/bin/ng build -source-map=false
node --max_old_space_size=2048 node_modules/@angular/cli/bin/ng build --source-map=false

```

# Nginx Config File 

```

server {
    listen 80;
    server_name yourdomain.com;  # Replace with your domain or IP address

    root /var/www/html/angular-app;  # Replace with the path to your Angular build directory
    index index.html;

    # Access and error logs
    access_log /var/log/nginx/angular-access.log;
    error_log /var/log/nginx/angular-error.log;

    location / {
        try_files $uri $uri/ /index.html;
    }

    # Optional: Add gzip compression
    gzip on;
    gzip_types text/plain text/css application/json application/javascript text/xml application/xml application/xml+rss text/javascript;
}

```





