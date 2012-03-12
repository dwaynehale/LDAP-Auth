#LDAP Auth for the CodeIgniter Framework for PHP
This is a simple two file library for CodeIgniter so that application users can authenticate against a Microsoft LDAP server (or OpenLDAP).
While this library does provide the ability to query user information from the LDAP server, it is very limited. I wouldn't expect this software to be bug free.

##What you'll need:
-ldap_auth.php

-ldap_auth_config.php

I'll assume that you'll be using this with a application you wrote in the CodeIgniter Framework for PHP 

##Usage
In order to use this plugin you must first initalize it in your controller:

```php
$this->load->library('ldap_auth');
```

Then you can call:

```php
$this->LDAP_auth->auth($username,$password);
```

or


```php
$this->LDAP_auth->info($username);
```

[![endorse](http://api.coderwall.com/dwaynehale/endorse.png)](http://coderwall.com/dwaynehale)