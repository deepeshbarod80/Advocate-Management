Advocate Management System Requirements

The Laravel framework has a few system requirements. All of these requirements are satisfied by the Laravel Homestead virtual machine, so it's highly recommended that you use Homestead as your local Laravel development environment.

However, if you are not using Homestead, you will need to make sure your server meets the following requirements:

PHP >= 7.1. 3
OpenSSL PHP Extension
PDO PHP Extension
Mbstring PHP Extension
Tokenizer PHP Extension
XML PHP Extension
Ctype PHP Extension
JSON PHP Extension
BCMath PHP Extension
* In most hosting accounts, these extensions are enabled by default. But you should check with your hosting provider.

After installation InfixAdvocate to work properly, you must make few directories/files writable. Below are a list of directories/files you should ensure that have write permissions.

installation_dir/storage/app/
installation_dir/storage/framework/cache
installation_dir/storage/framework/session
installation_dir/storage/framework/testing
installation_dir/public/uploads/
