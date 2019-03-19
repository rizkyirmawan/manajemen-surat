[![Build Status](https://img.shields.io/travis/bayubimantarar/suratapp.svg?style=flat-square)](https://travis-ci.org/bayubimantarar/suratapp)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/bayubimantarar/suratapp/pulls)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg?style=flat-square)](https://bimantara.web.id)


# Manajemen Surat Masuk & Surat Keluar
Manajemen surat masuk & surat keluar adalah sebuah aplikasi yang bertujuan untuk :
1. Memudahkan sekretaris pimpinan dalam mengadministrasikan surat masuk dan surat keluar
2. Memudahkan pencarian kembali surat masuk dan surat keluar
3. _paperless_, karena tidak perlu memperbanyak surat (_copy_)

## installation
1. Clone repository
2. Install dependencies composer

        composer install --no-dev #for production

        composer install #for development

3. Copy file environment

        cp .env.example .env

4. Generate application key

        php artisan key:generate

## Test
Test with phpunit

    ./vendor/bin/phpunit

Test with laravel dusk
    
    php artisan dusk
