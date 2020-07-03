Self-Hosted vs. Third-Party Email

Self-hosted email is probably my ideal, but for all sorts of practical reasons I inevitably go back to paying a third-party provider. It was bad enough when you had to worry about recipients not seeing your messages because their providers directed your messages to their spam folders – or, worse, completely discarded your messages without ever notifying you or your recipients. Microsoft was – and still is – notorious in this regard. The mysteriously unreliable algorithms that condemn a significant number of legitimate messages to the spam folder remain one of Microsoft’s many corporate secrets.

The situation today, though, is even worse. In addition to worrying about whether your recipients will ever see your messages, you now have to worry about the messages of your potential correspondents reaching your own mail server. Some email providers no longer deliver messages to privately run email servers. I discovered this during my most recent foray into self-hosting. I had mistakenly assumed that whatever trouble I might have getting my outbound messages into recipients’ inboxes, I at least would not have to worry about missing incoming messages because my third-party mail provider had ‘helpfully’ rejected them on suspicion of being spam. I discovered that some mail servers were not even attempting to deliver to my server. (Yes, my MX, rDNS, SPF, DKIM, and DMARC records were all properly configured and connections to my server were secured with a Let’s Encrypt certificate.) Subsequently, I discovered other email providers complaining about this same issue. [A discussion at the MXroute forum][mxr] confirmed that some email sending servers block sending to some destinations, presumably to the inexpensive servers that might be leased by an individual or small business.

So, at this point, I am back to relying on a third-party host for my email.

[mxr]: https://community.mxroute.com/t/verification-emails-from-u-haul/1275

Tags: email
