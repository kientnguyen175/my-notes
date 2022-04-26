## PHP
- Fatal error: Allowed memory size of 1610612736 bytes exhausted
  - B1: Cài [composer.phar](https://getcomposer.org/download/) riêng cho project
  - B2: ```php -d memory_limit=-1 composer.phar update```
