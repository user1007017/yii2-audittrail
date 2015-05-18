# Yii2-audittrail
Yii2-audittrail is a behavior and a set of widgets to track all modifications performed on a model


## Installation
The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```bash
$ composer require asinfotrack/yii2-audittrail
```

or add

```
"asinfotrack/yii2-audittrail": "dev-master"
```

to the `require` section of your `composer.json` file.


## Migration
	
After downloading everything you need to apply the migration creating the audit trail entry table:

	yii migrate --migrationPath=@vendor/asinfotrack/yii2-audittrail/migrations