# odoo-dev

How to deploy on development environment in an Odoo project.

## Clone repository

```
git clone https://github.com/crivero7/odoo-dev.git
```


## Project Layout

### Make executable script
Open Git Bash.

Into bin folder ~\odoo-dev\bin run the following command .

```
chmod -x .dev-env
```
Then, run .dev-env file

```
.\.dev-env file
```

## Environment variables
Create .env file into repository root ~\odoo-dev

```
DB_USER=amim
DB_HOST=127.0.0.1
DB_PASSWORD=admin
DB_NAME=AMIM
```


## Database config
Open Git Bash.

Into bin folder ~\odoo-dev\bin run the following command on Git bash.

```
chmod -x .db-setup
```
Then, run .db-setup file

```
.\.db-setup file
```

## Virtual environment

Activate virtual environment on repository root ~\odoo-dev

```
.\env\Scripts\activate
```

## Run service
Into repository root ~\odoo-dev run the following command

```
python .\src\odoo-bin -c odoo-dev.cfg
``