# Tapis Pods Interactive Notebook
Use this notebook to interact with Tapis Pods. Using `Fernet` from the `cryptography` package to encrypt and decrypt TACC password.
To use this notebook, create a directory call `SECRETS` and use `Fernet` to create a key and encrypt your password. Store your key in `SECRETS`. Lastly, create a json file called `Tapis_Login.json` and store your username in `username` and your encrypted password in `password`. 

```
>Tapis_Login.json

{
    username: TACC_ACCOUNT_NAME
    password: MY_ENCRYPTED_PASSWORD
}
```
# Installation
```
    python3 -m venv <virtual environment>
    pip install tapipy cryptography
```

Generate a secret key and encrypt your password (https://www.geeksforgeeks.org/how-to-encrypt-and-decrypt-strings-in-python/).

# Disclaimer
*Make sure to keep your key private.*