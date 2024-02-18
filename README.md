# mk_venv

Create and maintain python venvs.

I keep my venvs in a central location - `~/.local/lib/venv/*` which makes maintenance much easier.

Check out the [activate script](https://github.com/cn246-dotfiles/zsh/blob/main/.config/zsh/functions/activate) in my zsh dotfiles for easy activation of venvs!


## Installation
I used python3 with it's default modules to parse json, so there are no external dependencies required :)

Clone this repository and optionally symlink **mk_ec2** to somewhere in your `$PATH` so you can call it from anywhere.

----

## Usage
- Copy the included `settings.json.example` to **settings.json**.
- Edit **settings.json** with your desired venv configuration.
- Run the script:
```bash
./mk_venv
```

Updating the list of modules in **settings.json** and re-running the script will install or uninstall modules for that particular venv.

----

## Links
- https://docs.python.org/3/library/venv.html
