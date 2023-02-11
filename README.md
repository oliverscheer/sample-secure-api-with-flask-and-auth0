# How to Build Secure APIs with Flask and Auth0

Inspired by: <https://www.freecodecamp.org/news/build-secure-apis-with-flask-and-auth0/>

```
source .venv/bin/activate

pip install flask python-dotenv python-jose flask-cors six jsonify

flask --app myapp run
```

Access endpoint

```
curl -i http://localhost:5000
curl -i http://localhost:5000/user
curl -i http://localhost:5000/admin
```

Identifier: https://secure-python-flask-api

Auth0 Domain: dev-uotxuzaxx4zmno68.us.auth0.com

Read more: <https://auth0.com/blog/permission-based-security-aspnet-webapi/#Testing-Permissions>