<p align="center">
    <img src="https://github.com/filamentphp/filament/assets/41773797/8d5a0b12-4643-4b5c-964a-56f0db91b90a" alt="Banner" style="width: 100%; max-width: 800px;" />
</p>

<p align="center">
    <a href="https://laravel.com"><img alt="Laravel v12+" src="https://img.shields.io/badge/Laravel-v12+-FF2D20?style=for-the-badge&logo=laravel"></a>
    <a href="https://filamentphp.com"><img alt="Filament v5" src="https://img.shields.io/badge/Filament-v5-FDAE4B?style=for-the-badge&logo=filament"></a>
    <a href="https://php.net"><img alt="PHP 8.4+" src="https://img.shields.io/badge/PHP-8.4+-777BB4?style=for-the-badge&logo=php"></a>
</p>

## Setup

```sh
docker run --rm --interactive --tty \
  --volume $PWD:/app \
  --user $(id -u):$(id -g) \
  composer create-project --ignore-platform-reqs gabriel2m/filament-starter-kit {project_name}
cd {project_name}
./vendor/bin/sail up -d
./vendor/bin/sail composer setup
```

## License

Open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
