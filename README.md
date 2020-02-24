# Sane Defaults for GrumPHP

## Instructions for use

    "ergebnis/composer-normalize": "^2.2",
    "filp/whoops": "^2.1.12",
    "friendsofphp/php-cs-fixer": "^2.16",
    "friendsoftwig/twigcs": "^3.2",
    "jakub-onderka/php-parallel-lint": "^1.0",
    "laminas/laminas-development-mode": "^3.1",
    "maglnet/composer-require-checker": "^2.1",
    "mezzio/mezzio-tooling": "^1.0",
    "phpmd/phpmd": "^2.8",
    "phpro/grumphp": "^0.17.2",
    "phpstan/phpstan": "^0.12.11",
    "phpunit/phpunit": "^7.0.1",
    "roave/security-advisories": "dev-master",
    "sensiolabs/security-checker": "^6.0"


```bash
composer require --dev ergebnis/composer-normalize friendsofphp/php-cs-fixer \
jakub-onderka/php-parallel-lint maglnet/composer-require-checker phpmd/phpmd \
phpro/grumphp phpstan/phpstan phpunit/phpunit roave/security-advisories \
sensiolabs/security-checker

curl https://raw.githubusercontent.com/sane-defaults/phpcs/master/.php_cs > .php_cs
curl https://raw.githubusercontent.com/sane-defaults/grumphp/master/grumphp.yml > grumphp.yml
```
