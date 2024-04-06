# Firebase Email Tutorial

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/EVJOMYImHs0/1.jpg)](https://www.youtube.com/watch?v=EVJOMYImHs0)

Read More: 
`https://firebase.google.com/docs/extensions/official/firestore-send-email`

##SMTP Username Template: 
`smtps://username@smtp.provider.com:465`

##Email Document Schema
```
to: ['someone@example.com'],
message: {
  subject: 'Hello from Firebase!',
  text: 'This is the plaintext section of the email body.',
  html: 'This is the <code>HTML</code> section of the email body.',
}```
