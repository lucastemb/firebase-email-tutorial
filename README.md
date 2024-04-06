# Firebase Email Tutorial

# YouTube Video
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/EVJOMYImHs0/0.jpg)](https://www.youtube.com/watch?v=EVJOMYImHs0)

## SMTP Username Template: 
`smtps://username@smtp.provider.com:465`

## Email Document Schema
```
to: ['someone@example.com'],
message: {
  subject: 'Hello from Firebase!',
  text: 'This is the plaintext section of the email body.',
  html: 'This is the <code>HTML</code> section of the email body.',
}
```

Read More: 
`https://firebase.google.com/docs/extensions/official/firestore-send-email`
