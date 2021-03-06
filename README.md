# Harbor

Command-line tool to help dockerize Laravel. Built using [Laravel Zero](https://github.com/laravel-zero/laravel-zero).

## Installation

```bash
$ composer global require whatdafox/harbor
```

## Usage

Create a new Laravel application (using the [Laravel Installer](https://laravel.com/docs/5.7/installation#installing-laravel)):

```bash
$ laravel new MyApplication
```

Initialize Harbor:

```bash
$ harbor init
```

Boot your containers:

```bash
$ harbor up
```

To shut down the container, run:

```bash
$ harbor down
```

To see all running containers, run:

```bash
$ harbor ps
```

To run artisan commands, run:

```bash
$ harbor artisan [arguments & options]
```

To run composer commands, run:

```bash
$ harbor composer [arguments & options]
```

To run phpunit commands, run:

```bash
$ harbor phpunit [arguments & options]
```

To run any other commands, run:

```bash
$ harbor run  command [arguments & options]
```

## License

Harbor is an open-source software licensed under the [MIT license](https://github.com/whatdafox/harbor/blob/master/LICENSE.md).
