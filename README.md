# rest-koa2-api
RESTFul Koa2 API with Mongoose 

Accounts consist of _email_ (required) + _tags[]_ (optional)

1. POST /accounts to upsert (if exists, update. if not, create.) accounts
2. GET /accounts/emails/:tag to fetch all account emails w/ given tag
3. GET /accounts/tags/:email to fetch all tags for an account w/ given email

