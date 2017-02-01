salandur.php
============

Ansible role to manage PHP

### Example:

```yaml
- hosts: all

  roles:
    - salandur.php
```

### Variables

```yaml
php_modules: []
php_short_open_tag: Off
php_display_errors: Off
php_error_reporting: E_ALL & ~E_DEPRECATED
```

### License

Licensed under the MIT License. See the LICENSE file for details.

### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/salandur/salandur.php/issues)!
