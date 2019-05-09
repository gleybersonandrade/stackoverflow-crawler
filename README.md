# Stack Overflow Crawler

Stack Overflow crawler and code linter.

## Running

First, create the database with the model in DB folder, then run the following commands in order:

### Crawler

```
node crawler.js --language=<language> --year=<year> --month=<month> --day=<day>
```

or

```
node crawler.js --language=<language> --time=<timeinseconds>
```

### Populate

```
node populate.js --language=<language>
```

### Linter

```
node linter.js
```

## Auxiliar commands

Prepare database to receive data:

```
ALTER USER root IDENTIFIED WITH mysql_native_password BY '<password>';
```