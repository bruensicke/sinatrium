# Sinatrium

A Lithium micro framework.

## Usage

Add routes with closures.

```
Router::connect('/', array(), function($request) {
	$body = '<h1>Welcome to Sinatrium</h1>';
	return new Response(compact('body'));
});
```

Now, with PHP 5.4 goodness! Execute the PHAR from the command-line to run Sinatrium with PHP's built-in web server.

```
$ php lithium.phar

// OR

$ php lithium.phar -hlocalhost -p8000

// Visit http://localhost:8000 for Sinatrium goodness.
```

