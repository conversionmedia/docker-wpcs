# docker-wpcs
Dockerised PHP CodeSniffer with WordPress Coding Standards.

## Use with SublimeLinter3 on Mac OS X
Copy the files `phpcbf`, `phpcs` and `phpmd` to `/usr/local/bin`.
Specify the executable in the settings:
```
{
	"SublimeLinter": {
		...
		"linters": {
			"phpcs": {
				...
				"cmd": "/usr/local/bin/phpcs",
				...
			},
			"phpmd": {
				...
				"cmd": "/usr/local/bin/phpmd",
				...
			}
		},
		...
	}
}
```
