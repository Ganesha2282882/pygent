# pygent
NOTE: This software is not intended for spyware, like BonziBuddy.

Microsoft Agent Character for the 21st century
##
# To install
Put the pygent.py into your `sitepackages` directory. More info <a href="https://stackoverflow.com/questions/122327/how-do-i-find-the-location-of-my-python-site-packages-directory">here</a>.
##
# Example app that uses the library
You can base the app out of this:
> ```python
> # import the module
> import pygent
> # initalize the help
> pygent.assist("Welcome to {{app name}}!")
> pygent.character(pygent.characters("firefox"))
> # run the help program
> pygent.run()
> ```
##
# Characters
Available characters are:
> - `konqi`
> - `firefox`
> - `merlin`
> - `rover`

Or you can replace the `pygent.characters()` part with `repr()`ed ASCII art.
