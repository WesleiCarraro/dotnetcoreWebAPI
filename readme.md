# DotNetCoreWebAPI 

This is a dotnetcore WebAPI sample with CRUD operations under REST verbs of HTTP.

## Installation

TBD.


## Usage
Go to Postman or Insomnia or even by a CLI interface and hit:
```bash
curl --insecure https://localhost:5001/api/glossary

curl --insecure https://localhost:5001/api/glossary/jwt

curl --insecure \
  --verbose \
  --request POST \
  --url https://localhost:5001/api/glossary \
  --header 'content-type: application/json' \
  --data '{ "term": "MFA", "definition": "An authentication process that considers multiple factors."}'

curl --insecure \
  --request PUT \
  --url https://localhost:5001/api/glossary \
  --header 'content-type: application/json' \
  --data '{ "term": "JWT", "definition": "An open, industry standard RFC 7519 method for representing claims securely between two parties. Auth0 uses JWT format for ID Tokens."}'

curl --insecure \
  --request DELETE \
  --url https://localhost:5001/api/glossary/openid
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)