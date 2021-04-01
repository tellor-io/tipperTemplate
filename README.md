# Tellor TipperTemplate

## What can I use this for?
You can use this tool to request new on-chain Tellor oracle data, all without leaving github!

To get started, you will need to use this template, add some secrets to your repo, and edit the provided workflow.

## Using the template
1. Click the green "use this template" button. ![template demo](helper-images/use-this-template-button.png "Fork")
2. Navigate to repo settings. ![repo settings](helper-images/settings.png "Settings")
3. Navigate to repo secrets. ![repo secrets](helper-images/secrets.png "secrets")
4. Add the necessary repo secrets. ![add secret](helper-images/new-secret.png "add secret")

## What secrets will I need?
You can find the names of the github secrets to set on the `main.yml` file. Note: you will need to use these exact secrets titles verbatim.
* `PUBLIC_KEY` -- your account's public key
* `PRIVATE_KEY` -- your account's private key
* `MAINNET_NODE` -- your JSON-RPC mainnet endpoint. usually HTTP.
* `RINKEBY_NODE` -- your JSON-RPC rinkeby endpoint. usually HTTP.
* `GOERLI_NODE` -- your JSON-RPC goerli endpoint. usually HTTP.

## How can I update the workflow from github?
1. Navigate to `main.yml` in the `.github/workflows` directory.
2. Edit `main.yml` ![edit yml](helper-images/edit-yaml.png "editing")
3. From here, follow along with the comments to edit the workflow as needed.
4. Commit changes!