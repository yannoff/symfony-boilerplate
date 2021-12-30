# symfony-boilerplate

## Usage

```
composer create-project yannoff/symfony-boilerplate:dev-5.4-lts
```

_or_

```
docker run --rm -it \
    -u $UID:$GID \
    -w /src \
    -v $PWD:/src \
    -v $HOME/.composer:/.composer \
    yannoff/php-fpm:8.0 \
    composer create-project yannoff/symfony-boilerplate:dev-5.4-lts
```

## Available versions

- [6.x-dev](https://github.com/yannoff/symfony-boilerplate/tree/6.x-dev) The latest edge version
- [5.4-lts](https://github.com/yannoff/symfony-boilerplate/tree/5.4-lts) The `5.4 LTS` version
- [4.4-lts](https://github.com/yannoff/symfony-boilerplate/tree/4.4-lts) The `4.4 LTS` version
- [3.4-lts](https://github.com/yannoff/symfony-boilerplate/tree/3.4-lts) The `3.4 LTS` version

## License

Licensed under the [MIT License](LICENSE).
