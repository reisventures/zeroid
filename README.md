# zeroid
Lets make it easy for any website/app to authenticate users by asymmetric cryptography therefore, without having the need to identify the actual person.


The idea is simple, and probably I am not the firstone to speak about it: Just scan a QRCode and you are logged in, even on new websites where you do not have account yet!

This project aims to solve the following problems related to account creating and the identification/authentification process:

- It's boring to have to create a new account on every website;
- It would be nice (safer and less boring) not have to depend on email/sms for recovering access to my account on any website. Having in mind that those two (email and sms ) will be handled by other people or institutions. Even if you have your own private mail server, still it would be nice not to depend on it for identification/authentication on third parties websites;
- By entering the password/username in the websites every time you login you are doing a lot of exposure, therefore it would be safer not to have to insert it at all;

The concept of "2fa" or "Two Factor Autentication" has become common (and really useful) and most of the web systems that require greater security will relay on it to add extra security to the authentication process. Given this fact, I am assuming that most of people are used to the idea of using the smartphone as a means for security.  Following this line but changing slightly the paradigma we can than provide an authentication mehtod based on asymetric cryptography that allows for an authentication process that is safer, quiquer, easier and totally independent of any third parties, or emails, sms. The only tool necessary is the phone and the internet.
