# Bot-Template

A cookiecutter template for a discord bot with [dis-snek](https://github.com/Discord-Snake-Pit/Dis-Snek) made by [Kigstn](https://github.com/Kigstn)

Made for users to get started making discord bot easier.

# Installing

To install the template and get started making your own discord bot, run:

1) `pip install cookiecutter`
2) `cookiecutter https://github.com/Kigstn/Bot-Template`


## Arguments

- `project_name`: The name of your project
- `project_slug`: A formatted version of your project name, which is used as a filepath and for the docker container names
- `license`: What license your project should have. Can be safely ignored should you not plan on openly publishing this project on the internet
- `license_organization`: The name that should appear on the license
- `load_debug_commands`: If some helpful debug commands should be loaded. These will only be accessible to the owner of the bot
- `discord_token`: Your discord bot token. This will not be pushed if your use this project with git
