# heroku-buildpack-bolstr-settings Buildpack

This is a [Heroku buildpack][0] for decrypting an environment-specific set of config variables.

It expected 3 config variables to be set:

1. ```DOTENV_ENCRYPTED_FILE``` is the name of the file that contains the encrypted configuration (e.g., ".env.production.encrypted")
1. ```DOTENV_PLAINTEXT_FILE``` is the name of the file to decrypt to (e.g., ".env")
1. ```DOTENV_ENCRYPTION_KEY``` is the key used to decrypt the file

It's used by Bolstr to automate maintenance of our config vars.

--

[0]: http://devcenter.heroku.com/articles/buildpacks
