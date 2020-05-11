

## Installation and use

<pre>
$ git clone https://github.com/kawshar798/multi-auth.git
</pre>
<pre>
$ cd  multi-auth
</pre>
<pre>
$  cp .env.example .env
</pre>

##Change configuration according to your need in ".env" file and create Database

<pre>
$ composer install
</pre>
<pre>
$ php artisan migrate
</pre>
<pre>
$  php artisan db:seed
</pre>

Now visit and login:http://localhost/multi-auth/
----Admin---
gmail: admin@gmail.com
password: 12345678

----Author---
gmail: author@gmail.com
password: 12345678

- [DatabaseDesign](https://drawsql.app/kas/diagrams/multi-auth).
