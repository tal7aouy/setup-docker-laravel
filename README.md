
# Setup Docker For Laravel 9

Setup docker for laravel projects in an easy way, clone the repo and put it in your own project.

### Usage

Clone repository

```sh
git clone https://github.com/tal7aouy/setup-docker-laravel.git
```
Copy the docker repository to your laravel project
```sh
cp -rf setup-docker-laravel/*  blog/
```
```sh
cd blog/
```


run 

```sh
docker-compose up -d
```

Acess to a container
```sh
docker-compose exec app bash
```

Install composer dependencies 
```sh
composer install
```

## Credits
- [Mhammed Talhaouy](https://github.com/tal7aouy)

## License
Please see [License File](LICENSE.md) for more information.
