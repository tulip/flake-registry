# Tulip Nix registry

This repo hosts a pointer to all the flakes that we use at tulip
This is a json file that lets us run `nix run ponte -- -help` or `nix shell idd`  or (eventually) `nix run oplogtoredis`

### Usage 

To use, modify ~/.config/nix/nix.conf to add the following line:

```
flake-registry = https://github.com/tulip/flake-registry/releases/download/v1.2.0/flake-registry.json
```

Where `v1.2.0` should be replaced with the most recent version.
