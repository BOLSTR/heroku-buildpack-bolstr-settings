# heroku-buildpack-bolstr-settings Buildpack

This is a [Heroku buildpack][0] for decrypting an environment-specific set of config variables.

It expects DOTENV_ENCRYPTION_KEY to be defined in the environment.

It's used by Bolstr to automate maintenance of our config vars.

--

[0]: http://devcenter.heroku.com/articles/buildpacks
