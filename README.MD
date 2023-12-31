### ToDo

- [x] Register User

  - [x] Validate - name, email, password - with Mongoose
  - [x] Hash Password (with bcryptjs)
  - [x] Generate Token
  - [x] Send Response with Token
  - [x] Hash pasword in the model
  - [x] Generate Token with a fn in the model

- [x] Login User

  - [x] Validate - email, password - in controller
  - [x] If email or password is missing, throw BadRequestError
  - [x] Find User
  - [x] Compare Passwords
  - [x] If no user or password does not match, throw UnauthenticatedError
  - [x] If correct, generate Token
  - [x] Send Response with Token

- [x] Mongoose Errors

  - [x] Duplicate (Email)
  - [x] Validation Errors
  - [x] Cast Error

- [x] Security
  - [x] helmet
  - [x] cors
  - [x] xss-clean
  - [x] express-rate-limit

Swagger UI

```yaml
/jobs/{id}:
  parameters:
    - in: path
      name: id
      schema:
        type: string
      required: true
      description: the job id
```
