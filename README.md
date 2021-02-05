# Revo sports asia

### Installation

This project requires [Composer](https://getcomposer.org/) to run.

After setting up the composer, Install the dependencies and devDependencies and start the server.
```sh
$ composer install
```

Create a new wp-config file,
```sh
$ cp wp-config-sample.php wp-config.php
```

To make installation secure we will keep the .env file outside of public_html folder. Make sure to change the level according to your directory structure,
```sh
$ mkdir '../project_name-config' && cp .env.example '../project_name-config/.env'
```

Now we need to setup our wp-env.php file. Again change the location of directory accordingly.
```sh
$ touch 'wp-env.php' && printf '<?php $envFileLocation = "/../project_name-config"; ?>' > wp-env.php
```
## Author
[Rohan Sharma](mailto:rohan@rensans.com)
