<p align="center"><img src="./public/images/readme/spike.svg" width="400"></p>

## Como instalar

> atenção é preciso ter o composer instalado

```
git clone git@github.com:AndreMart/cart-laravel.git

```

```
php artisan install

```

```
php artisan key:generate
```

### Crie sua base de dados

### copie e cole o arquivo .env.example para .env

### atribua os valores pertinentes

```
DB_CONNECTION=mysql
DB_HOST=localhost
DB_PORT=SUA PORTA GERALMENTE 3306
DB_DATABASE=SUA BASE DE DADOS
DB_USERNAME=USUARIO
DB_PASSWORD=SENHA
```

### atualmente se utiliza mercado pago com Tokenizer

### crie uma conta no mercado pago

### pegue sua setAccessToken e adicione em CarrinhoController
```
 SDK::setAccessToken("Aqui")
```

### Adicione em cart.blade sua  data-public-key

```
 data-public-key="Aqui"
```

### após isso rode os seguintes comandos separadamente
```
php artisan migrate

php artisan db:seed

```
### dados de entrada do sistema estão no arquivo /databases/seeds/UserTableSeeder

```
php artisan serve

```

### url: 127.0.0.1 acesso ao front cliente

### url: 127.0.0.1/admin acesso ao admin

### Adicione webbaners

### adicione categorias

### adicione produtos para as categorias pertinentes

<p>by: André Martins</p>

