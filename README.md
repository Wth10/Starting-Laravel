<p align="center"><a href="#" target="_blank"><a><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

INSTALANDO O LARAVEL E AUTENTICAÇÃO DE USUARIO COM O USO DO **BREEZE**, ABAIXO SÃO OS PROGRAMAS ÚTILIZADOS E NECESSARIOS PARA O SEU PROJETO.

<br>

_[Node Js](https://nodejs.org/en/)_ Instale a versão _LTS_

_[Composer](https://getcomposer.org/)_

_[Laravel](https://laravel.com/docs/8.x#installation-via-composer)_

<br>

INSTALADO O LARAVEL VIA COMPOSER, CRIANDO UMA PASTA PARA O SEU PROJETO ABRA O **TERMINAL** NA PASTA, E DIGITE OS COMANDOS ABAIXO.

```PHP
    composer create-project laravel/laravel (Nome Projeto)

    cd (Nome Projeto)
```

<br>

PRONTO O LARAVEL ESTA INSTALADO, PARA DA UM START NO SERVIDOR LARAVEL USE O CODIGO ABAIXO, PARA FECHAR O SERVIDOR APERTE 'CTRL + C'.

```PHP
    php artisan serve
```

<br>

FEITO ISSO PRONTO VOCÊ JÁ ESTA COM O LARAVEL INSTALADO. MAS ANTES VOCÊ PRECISA CONFIGURAR O BANCO DE DADOS NOS ARQUIVOS DO SEU PROJETO E ACESSE `.env` EM `DB_DATABASE` COLOQUE O NOME DO BANCO DE DADOS CRIADO PARA O SEU PROJETO.

---

## Instalando Laravel Breeze

<br>

PARA INSTALAR O BREEZE É NECESSARIO TER O **NODE JS** INSTALADO NO SEU PC, SEGUE OS CODIGOS ABAIXO PARA INSTALAÇÃO.

```PHP
    composer require laravel/breeze --dev

    php artisan breeze:install

    npm install

    npm run dev

    php artisan migrate
```

<br>

EM CASO DE ERRO `npm` TENTE ISSO CODIGO ABAIXO.

```PHP
    npm install -g node

    npm install --global cross-env

    npm install autoprefixer@9.8.0

    npm install

    run dev
```

<br>

PRONTO AGORA VOCÊ JÁ ESTA COM O LARAVEL INSTALADO E ESTA PRONTO PARA COMEÇAR O SEU PROJETO, EM CASO DE DUVIDAS ESSE É O SITE [OFICIAL DO LARAVEL](https://laravel.com/).
