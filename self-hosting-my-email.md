Self-Hosting My Email

Over the years, I have periodically set up and run my own email server. For the most part, these experiments were simply for learning purposes. I wanted to understand for myself what was involved in running a mail server, but I always took for granted that I would entrust the hosting of my primary email address to someone else -- someone who maintained mail servers for a living, someone working full-time at maintaining the mail server where my address would be managed.

Through all these years, though, I never found an email provider that fully suited me. There are a number of solid, reliable email hosts out there. Inevitably, though, there would be details about each of their services that bothered me. I ended up migrating from one email host to another, never quite satisfied with any of them. So, a couple of weeks ago, I bit the bullet and moved email for my primary domain to a server I am managing myself. Today, I moved email for my secondary domain to that server as well. (Don't worry: I have additional, lower-priority MX records pointing to a backup email solution.)

The final straw was discovering that my provider was silently discarding legitimate messages in an overly aggressive attempt to combat spam. Some of these were personal messages. Some were log-in verification codes that some services send when you log in from a new IP address. The point is that these messages were definitely not spam. I wanted to receive them. In the case of the log-in verification codes, I needed them. If the provider thought that the messages were suspicious, then the messages could have been directed to a spam folder. They weren't. They were simply discarded before they ever reached my account. That is a deal breaker for me.

I don't know how long my foray into self-hosting will last. It may be just another leg of the journey in my restless migration from one host to another. I do know this, though: I really like being able to look at the server logs myself. I'm not sure I could go back to a solution where I cannot do that.

Tags: email
