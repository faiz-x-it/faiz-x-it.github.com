Information
Andreas Asatera Sandi Nofa
Last Updated:
Yesterday at 8:47
Goals
Goals dari project ini yaitu melakukan migrasi project Quantumbook dari   
Link Project Quantumbook Code Igniter: https://github.com/Vokanesia/quantumbook (php 7.4)
Link Project Quantumbook Laravel: https://github.com/Vokanesia/quantumbook-laravel (php 8.1)

Note
Template landing page sudah ada di repository Quantumbook Code Igniter
Template dashboard area menggunakan Qovex

Gunakan alur pengerjaan menggunakan Git Flow
Referensi:
https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow
https://danielkummer.github.io/git-flow-cheatsheet/

Good Developer Write Test!!!
Disarankan dalam pengembangan aplikasi menggunakan workflow Test Driven Development (TDD). Referensi: https://blog.nafies.id/tdd-laravel/

Design Pattern
Pengerjaan fitur diharap menerapkan Service Layer. Command utk membuat service class sebagai berikut:

Bash
php artisan make:service-layer ClassName
Referensi: https://medium.com/@mhdnauvalazhar/design-pattern-implementasi-service-layer-di-laravel-cea01f64f57e

Penataan Struktur Folder Asset
Asset JS & CSS letakkan di public dengan struktur:

Bash
assets > type (dashboard / landing page) > js / css / images / dll
