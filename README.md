# php-extended-with-mail

php-extended-with-mail:
	restart: always
	image: grossmane/php-extended-with-mail
	volumes:
		# CONFIG
		- /path/to/ssmtp.conf:/etc/ssmtp/ssmtp.conf:ro
