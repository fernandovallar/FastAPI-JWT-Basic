## Setup
- create a .env containing:
    - POSTGRES_DB, 
    - POSTGRES_USER
    - POSTGRES_PASSWORD
    - POSTGRES_HOST
    - POSTGRES_PORT
    - SECRET_KEY
- build the app docker image:
    - ```docker build . -t fastapiapp```

## Running the app
```docker-compose up --build```


## Docs
Based on this [guide](https://dev.to/spaceofmiah/jwt-authentication-in-fastapi-comprehensive-guide--c0p
)

