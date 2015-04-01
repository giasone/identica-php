Identi.ca-php is a complete and easy to use PHP library to interact with identi.ca platform. Seems like it works, with some tricks, with other StatusNet (ex laconi.ca) like application. Please contact me or post a comment if you use it in your project or if you do something interesting...
Thanks!!!

## USAGE ##

Include the main library file

```
require_once("identica.lib.php") or die("Couldn't load Identi.ca library");
```

Create object using your credentials (username and password)

```
$identica = new Identica($username, $password);
```

The updateStatus() method updates your status. The message must be encoded in UTF-8:

```
$identica->updateStatus('Hello world!');
```

See the documentation in dowload or the wiki page for the complete functions list.





Sponsored by [![](http://www.jasone.it/logo/logo.png)](http://www.jasone.it/)