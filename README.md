# Nogopy
# We provide this repository to make OAuth and OpenId Connect clear 😎
# 1. What happened before OAuth
There are 3 major actors:
* You: Resource owner - and you do have a pair off username/password
* Resource server: Containing your data such as profile picture, date of birth
* Third party service

Scenario: Third party service wants to access your resource, how would you share them?
* The worst way to delegate access is to share your username/password to the third party

Some drawbacks on this approach:
* 3rd party needs to take time and effort to store your username/password
* You don't have ability to limit the 3rd party to access a limited resource or restrict access duration. Basically, the 3rd party can do whatever you can
* You have more than one 3rd parties, you cannot revoke access to an individual 3rd party, cause they all use the same username/password. What you can do is to change username/password and announce them all about the updated data



# 2. Motivation for OAuth
## I swear that you've come across this situation before:
* Open a website: nogopy.com 
* Click login button
* See screen: Login with Facebook or Google
* You hit consent button that allows nogopy.com to access your Facebook email and profile picture
* Then you log in successfully on nogopy with your Facebook profile 

## That is OAuth

# 3. What exactly is OAuth:
* It's not and API or a service: It's an open standard for authorization, so what is open here? Open means you can implement it by your own way
* 

# 2. Some OAuth terminologies
# 3. How it works
# 4. Get your hand dirty with some codes