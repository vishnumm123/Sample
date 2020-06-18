npm install -D json-server json-server-auth




{
  "users": []
}




json-server db.json -m ./node_modules/json-server-auth



POST /register
{
  "email": "olivier@mail.com",
  "password": "bestPassw0rd",
  "firstname": "Olivier",
  "lastname": "Monge",
  "age": 32
}



POST /login
{
  "email": "olivier@mail.com",
  "password": "bestPassw0rd"
}