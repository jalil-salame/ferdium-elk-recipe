# Elk Recipe

A Ferdium Recipe for the [Elk](https://elk.zone) Mastodon Client

## Usage

1. Download the code to this repo, you can use this url:
   https://github.com/salameme/ferdium-elk-recipe/archive/refs/heads/main.zip
2. Based on your OS (see [below](#Install-Recipe)) extract the code to the
   OS specific folder.
3. [Enable the Service](#Enable-Service)

### Install Recipe

#### Linux

Extract the code (see [Usage](#Usage)) to `~/.config/Ferdium/recipes/dev/elk/`,
or, if you changed `$XDG_CONFIG_HOME`, then extract to
`${XDG_CONFIG_HOME}/Ferdium/recipes/dev/elk/`

#### Windows (untested)

Extract the code (see [Usage](#Usage)) to `%appdata%/Franz/recipes/dev/`

#### MacOS (untested)

Extract the code (see [Usage](#Usage)) to `~/Library/Application Support/Franz/recipes/dev/`

### Enable Service

1. Click the `Add new Service` button on the bottom left of the UI, you can also
   use the `Services` context menu, or use the sortcut `Ctrl+N` (might be
   different for Macs)
2. Select `Custom Services`, Elk should be listed there

## Known Issues

- The notification badge is missing (see [#1][issue-1])

[issue-1]: https://github.com/salameme/ferdium-elk-recipe/issues/1
