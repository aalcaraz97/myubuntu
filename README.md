# myubuntu

Sets up my Ubuntu 16.04 Desktop System (experimental)

To execute it, you must login with your username (must be sudoer) to a clean Ubuntu 16.04/18.04 Desktop installation:

### Full Installation

This Ubuntu config is installed by running one of the following commands in your terminal as the main user of this desktop. 
You can install this via the command-line with `wget`. 


```shell
bash -c "$(wget https://raw.githubusercontent.com/jig/myubuntu/master/install-all.sh -O -)"
```

### Partial Installation

You can install just one item just invoking one of the `install-?.sh` scripts; for instance:

```shell
bash -c "$(wget https://raw.githubusercontent.com/jig/myubuntu/master/install-awscli.sh -O -)"
```

# VMware

If you are installing a virtual machine (VMware) it is recomeded to install its drivers (they are not installed by default)

```shell
bash -c "$(wget https://raw.githubusercontent.com/jig/myubuntu/master/install-vmguest.sh -O -)"
```

## note

`install.sh` script (was) based on [robbyrussell/oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
