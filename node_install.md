# Installing Node.js

## pre-req


### Make sure you have curl installed
```
sudo apt install curl
```


### Update and Upgrade system packages

```
sudo apt update && upgrade
```

## Download and install NVM


```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
```


###  Initializing NVM

```
 export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")" 
 [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
```

 This will load nvm 


### Verify nvm installation:
```
command -v nvm
```

