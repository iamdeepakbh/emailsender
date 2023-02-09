# emailsender
Quick Note: Google Security Updates
A recent Google update to their terms and features means you have to do an extra step to be able to send emails. Otherwise, you will see this error:
raise SMTPAuthenticationError(code, resp)
smtplib.SMTPAuthenticationError: (535, b'5.7.8 Username and Password not accepted. Learn more at\n5.7.8  https://support.google.com/mail/?p=BadCredentials x3-20020a17090a1f8300b00230e733599esm2583635pja.48 - gsmtp')

In the case that you are sending emails through GMAIL,  just go to your account(gmail) -> Account setting -> Scroll to the bottom of the page and you see Less Secured Apps tab ,now you just have to turn that feature ON. for more info visit this:

Links Less Secured Apps : https://support.google.com/accounts/answer/6010255
Third party sites & apps: https://support.google.com/accounts/answer/3466521

The reason that Google blocks this is because they do not trust your "app". Google states:
Less secure apps & your Google Account: If an app or site doesn’t meet our security standards, Google might block anyone who’s trying to sign in to your account from it. Less secure apps can make it easier for hackers to get in to your account, so blocking sign-ins from these apps helps keep your account safe.


I recommend turning that feature back OFF once done experimenting with email since it is an extra security feature for your gmail account.
