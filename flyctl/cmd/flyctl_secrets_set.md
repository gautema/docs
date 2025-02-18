Set one or more encrypted secrets for an application

## Usage
~~~
flyctl secrets set [flags] NAME=VALUE NAME=VALUE ...
~~~

## Options

~~~
  -a, --app string      Application name
  -c, --config string   Path to application configuration file
      --detach          Return immediately instead of monitoring deployment progress
  -h, --help            help for set
      --stage           Set secrets but skip deployment for machine apps
~~~

## Global Options

~~~
  -t, --access-token string   Fly API Access Token
      --verbose               Verbose output
~~~

## See Also

* [flyctl secrets](/docs/flyctl/secrets/)	 - Manage application secrets with the set and unset commands.

