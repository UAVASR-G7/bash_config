# Bash Config
This repository contains the bash config files ('.bashrc') for both the UAV and GCS computers.
The config can be applied by using the stow command from the `bash_config` directory followed by the desired config to apply.

## UAV Config
```bash
cd ~/.bash_config/
stow uav
```

## GCS Config
```bash
cd ~/.bash_config/
stow gcs
```

## Requirements
This approach described here requires the `stow` package to be installed. This can be done as seen below.
```bash
sudo apt-get install stow
```

Alternatively, a similar result can also be achieved by either copying/moving the `.bashrc` files or by creating simlinks using the `ln -s` command.
