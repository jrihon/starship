# Starship


Install [Starship](https://starship.rs/) to use these prompts

Store these files in the `~/.config/` directory. I use the JetBrainsMono NerdFont.

I use two different prompts
 - Everyday use : starship.toml
 - Use inside of tmux : tmux\_starship.toml

### Tmux prompt

To have the `tmux_starship.toml` active in `tmux`, paste the following into your `~/.bashrc` .
```sh
# Initiliase starship prompt for tmux
if [ -n "$TMUX" ]; then
    export STARSHIP_CONFIG=~/.config/tmux_starship.toml
fi
```
