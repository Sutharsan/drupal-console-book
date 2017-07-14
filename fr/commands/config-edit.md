# config:edit
Éditer la configuration sélectionnée.

**application.gitbook.messages.usage:**
```
drupal config:edit [arguments]
ced
cdit
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
config-name | Nom de la configuration.
editor | Editeur.

## application.gitbook.messages.examples
* Edit system cron configurations with "vim" (default editor).
```
drupal config:edit system.cron
```
* Edit system cron configurations with "gedit".
```
drupal config:edit system.cron gedit
```