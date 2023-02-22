This respository is just for training typescript and solid concepts.

How to run:
```
1 - clone the repository
2 - configure your mailtrap credentials in src/providers/implementations/MailTrapMailProvider.ts
3 - run: yarn (or npm install)
4 - run: yarn start (or npm run start)
5 - make a POST request in http://localhost:3333/users sending the following body:
{
name: "your name",
email: "your@email.com",
password: "yourpassword",
}
```

In your mailtrap you will see the welcome mail.

See ya.
