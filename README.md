# ssh_deploykeys

this script is meant to be run on new linux servers of Excellgene SA, it will try to download the public key of users specified in `users` file from github and add it to the file `authorized_keys` 

## Usage

    curl -s https://github.com/excellgene/ssh_deploykeys/


## Requirements

* curl 

```bash
    sudo apt update && sudo apt install curl
```