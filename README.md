# Sane Defaults for GrumPHP

## Instructions for use

```bash
composer require --dev phpro/grumphp phpstan/phpstan povils/phpmnd \
    sebastian/phpcpd sensiolabs/security-checker nikic/php-parser  \
    friendsofphp/php-cs-fixer jakub-onderka/php-parallel-lint \
    phpmd/phpmd

curl https://raw.githubusercontent.com/sane-defaults/phpcs/master/.php_cs > .php_cs
curl https://raw.githubusercontent.com/sane-defaults/grumphp/master/grumphp.yml > grumphp.yml
```
