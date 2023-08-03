# awsm.fish [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Fish is the sassy & user-friendly command line shell you never knew you needed for Linux, macOS, and the whole gang. Out with the old-fashioned shells that skimp on features for the sake of every last byte of RAM—finally, a command line shell for the 90s!

Welcome to the ultimate treasure trove of handpicked plugins, prompts, and other [Fish](https://fishshell.com/) goodies. You see, this isn't just any collection—we curate only the best of the best Fish projects for your friendly interactive shell. Got a top-notch project you want featured here? [Send us a pull request](https://github.com/jorgebucaran/awesome-fish/fork), join the crew!

## Contents

- [Official Resources](#official-resources)
- [Community Resources](#community-resources)
- [Prompts](#prompts)
- [Plugins](#plugins)
- [Docker](#docker)

## Official Resources

- [Official Site](https://fishshell.com)
- [GitHub Repository](https://github.com/fish-shell/fish-shell)
- [Try in browser!](https://rootnroll.com/d/fish-shell/) 🍤

## Community Resources

- [r/fishshell](https://www.reddit.com/r/fishshell) - The Reddit hangout
- [Gitter Channel](https://gitter.im/fish-shell/fish-shell) - Come chat with us!
- [Stack Overflow `#fish`](https://stackoverflow.com/questions/tagged/fish) - Got questions? We've got answers!
- [The Fish Cookbook](https://github.com/jorgebucaran/cookbook.fish) - From Shell to Plate: Savor the Zest of Fish 🦞
- [cheatsheet](https://devhints.io/fish-shell)


## How to search plugin

For example, you want to search plugin related to fzf:
https://github.com/search?q=fzf+topic%3Afish-plugin

## Prompts

- [Tide](https://github.com/IlanCosman/tide) - A modern prompt manager for Fish
- [Pure](https://github.com/pure-fish/pure/) - [_That_](https://github.com/sindresorhus/pure) ZSH prompt, now in Fish flavor
- [Hydro](https://github.com/jorgebucaran/hydro) - Lag-free prompt with async Git status (ooh la la)
- [starship](https://github.com/starship/starship) -  Customizable prompt for any shell

## Plugins

### manager
- [Fisher](https://github.com/jorgebucaran/fisher) - Manage functions, completions, bindings, and snippets from the CLI.
- [Fundle](https://github.com/danhper/fundle) - `config.fish`-based plugin manager.
- [tacklebox](https://github.com/justinmayer/tacklebox)

### directory jump
- [z](https://github.com/jethrokuan/z) - Pure-Fish [`rupa/z`](https://github.com/rupa/z)-like directory jumping.
- [zoxide](https://github.com/ajeetdsouza/zoxide) - Supports all major shells.
- [fish-fastdir](https://github.com/danhper/fish-fastdir) - Fast directory navigation for fish

### history search
- [fzf](https://github.com/PatrickF1/fzf.fish) -  Fzf plugin for Fish.
- [peco](https://github.com/oh-my-fish/plugin-peco) - Browse your fish history with peco.
- [mcfly](https://github.com/cantino/mcfly) - Supports all major shells.
- [hiSHtory](https://github.com/ddworken/hishtory) - Better Shell History
- atuin

### work like bash
- [bass](https://github.com/edc/bass) - Make Bash utilities usable in Fish shell
- [Replay](https://github.com/jorgebucaran/replay.fish) - Run Bash commands replaying changes in Fish. 
- [Pufferfish](https://github.com/nickeb96/puffer-fish) - Text Expansions for Fish.
- [!!](https://github.com/oh-my-fish/plugin-bang-bang) - Bash style history substitution for Oh My Fish
- [fishbang](https://github.com/BrewingWeasel/fishbang) - Bash bang command for fish
- [fc](https://github.com/lengyijun/fc-fish) - fc command in fish
- https://github.com/fish-shell/fish-shell/wiki/Bash-Style-Command-Substitution-and-Chaining-(!!-!$)

### git
- https://github.com/wfxr/forgit
- [GitNow](https://github.com/joseluisq/gitnow) - A collection of utility functions to speed up your git workflow

### environment variable
- [direnv](https://github.com/direnv/direnv) - Load and unload environment variables depending on the current directory

### Node version manager
- [nvm](https://github.com/jorgebucaran/nvm.fish) - Node.js version manager lovingly made for Fish
- [fnm](https://github.com/Schniz/fnm) - Fast and simple Node.js version manager, built in Rust

### Write completions
https://github.com/adaszko/complgen

### other plugin
- [Done](https://github.com/franciscolourenco/done) - Automatically receive notifications after a long process finishes
- [Spark](https://github.com/jorgebucaran/spark.fish) - Sparklines for Fish
- [Fisher](https://github.com/jorgebucaran/fisher) - Manage functions, completions, bindings, and snippets from the CLI
- [Fundle](https://github.com/danhper/fundle) - `config.fish`-based plugin manager
- [Sponge](https://github.com/meaningful-ooo/sponge) - Clean command history from typos automatically
- [Autopair](https://github.com/jorgebucaran/autopair.fish) - Auto-complete matching pairs in the Fish command-line. ([Alternative](https://github.com/laughedelic/pisces))
- [Getopts](https://github.com/jorgebucaran/getopts.fish) - CLI options parser (alternative to the [`argparse`](https://fishshell.com/docs/current/cmds/argparse.html) builtin)
- [Fishtape](https://github.com/jorgebucaran/fishtape) - TAP-based test runner for Fish
- [Projectdo](https://github.com/paldepind/projectdo) - Context-aware single-letter abbreviations to build, run, and test any project
- [Virtualfish](https://github.com/adambrenecki/virtualfish) - Virtualenv wrapper
- [Async Prompt](https://github.com/acomagu/fish-async-prompt) - Make your prompt asynchronous
- [Apple Touchbar](https://github.com/rodrigobdz/fish-apple-touchbar) - Customize your [Touch Bar](https://developer.apple.com/design/human-interface-guidelines/macos/touch-bar/touch-bar-overview) in iTerm2
- [Abbreviation Tips](https://github.com/Gazorby/fish-abbreviation-tips) - Remembering abbreviations by displaying tips when you can use them
- [last-working-dir](https://github.com/kfkonrad/last-working-dir-fish-pkg) - Always open new fish shells in your last working directory
- [fish-colored-man](https://github.com/decors/fish-colored-man) - Color-enabled man pages plugin 
- [autocd](https://github.com/lengyijun/autocd-fish) - Auto fill `cd xxx` after `git clone xxx`
- [f](https://github.com/sudormrfbin/f) - Quickly get to a previously mentioned file in fish shell -- z for files !
- [Base16 Fish](https://github.com/FabioAntunes/base16-fish-shell) - A pure Fish solution to change your shell's default ANSI colors

## Fish script formatter
- `fish_indent`
- https://github.com/bmalehorn/vscode-fish

## Useful functions
- https://github.com/razzius/fish-functions

## Appimage

https://github.com/fish-shell/fish-shell/issues/6475

## Docker

- [Alpine Image](https://hub.docker.com/r/purefish/docker-fish)
- [Ubuntu LTS Image](https://hub.docker.com/r/dideler/fish-shell)
