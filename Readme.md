# Tapis Pods Notebook
Use this notebook to interact with Tapis Pods. Using `Fernet` from the `cryptography` package `pip install cryptography` to encrypt and decrypt TACC password.
To use this notebook, create a directory call `SECRETS` and use `Fernet` to create a key and encrypt your password. Store your key in `SECRETS`. Lastly, create a json file called `Tapis_Login.json` and store your username in `username` and your encrypted password in `password`. 


Tapis_Login.json
```
{
    username: TACC_ACCOUNT_NAME
    password: MY_ENCRYPTED_PASSWORD
}

```
# Disclaimer
*Make sure to keep your key private.*