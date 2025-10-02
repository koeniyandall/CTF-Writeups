# Intro to Burp

### I used Burp Suite via Portswigger in order to pen test a web site. With Burp, you can edit packets send to the website and see exactly what fields there are aswell as whether it was a POST or GET command. After getting past the Login screen, it provides you with a OTP code prompt. Normally, you would no be able to get past this step if you did not have access to the phone number, however, simply deleting the variable 'otp' was able to bypass the OTP and got us to our flag!  
