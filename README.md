# Deca Backend

Deca Mega Project for project management and microservices.

## Installation

Used [Laravel](https://laravel.com) as the backend and used [composer](https://getcomposer.org) to install Deca Project.

```bash
sudo git clone https://github.com/naingaunglinn/deca-backend.git
```
Copy the .env.example 

Linux
```bash 
sudo cp .env.example .env
```

Windows
```bash
copy .env.example .env
```

Install require library
```bash
composer install
```

Run sail for docker container
```bash
./vendor/bin/sail up -d
```

For development Migration
```bash
./vendor/bin/sail artisan migrate:fresh --seed
```
