# Getting Started With Das Keyboard Q Software - beta

=================== TODO read TODOs in this doc...==========================

*Warning:* the Q software is in very early stage. It's buggy, incomplete, poorly document
and below all expectations, that means it is a start and it's improving fast. Only use it if you are 
conformtable being a beta tester and contributing useful feedback.

## Installation
### Download and install Q clients
Q clients can be downloaded from the Q website:
  http://q.daskeyboard.com/

Q clients are available for different platform:
 - Q Desktop: Windows, Linux, Mac coming soon.
 - Q Mobile: Android
 
### Create a Das Keyboard Q account
In order to use the Q clients, you'll need to create an account at
 http://q.daskeyboard.com/ 

### Optional: signup for the Q forum 
 This is where we interact with each other: http://qforum.daskeyboard.com 

## Sending Signals to your 5Q keyboard
A bit of lingo first: a *signal* is a message that contains color information (and more) to be
displayed on a 5Q keyboard. All 3rd party platforms communicate to the 5Q clients by sending 
 signals very much like your friends send you text messages on your phone. 

Even without a real 5Q keyboard, you can play with Signals by creating, updating and deleting them. 
Signals will be display on the Q desktop "dashboard mode" and the Q Android app.

There are several possibilities to send signals to the 5Q keyboard:
 
 - Zapier (https://zapier.com): use Zapier clould platform to create zaps (like IFTTT recipes). 
 Select the Action called "Q-App". Zapier will create signals based on triggers such as
  emails, Facebook events, even new Youtube videos and much more.
 
 - TODO local API: see documentation at https://github.com/DasKeyboard/q/blob/master/README.md.
 - TODO Q cloud API: see documentation at https://github.com/DasKeyboard/q/blob/master/README.md.

## Contributing
At this point of the development, we would like to ask the community for input on all aspects
 of the project: features, API, ideas, etc... 
 Please use the forum to do this: http://qforum.daskeyboard.com.
 

## Roadmap
### Comming soon
 - Mac desktop app
 - Multi-key signals 
 - More lighting effects
 - SDK to create apps that talks to the 5Q
 - RGB profile sharing marketplace (open source and free)
 - Q apps sharing marketplace (open source and free)
 - TODO: add more here...


### TODO

# Known issues

- Q cloud server is slow, very slow. Of course, we are working on it.
- HTTPS is not implemented for the moment, but will be very soon.
- Some breaking changes will be made on the Signals API, so if something does not work anymore,
 make sure you are using the last version of the API 

Please refer to this link: https://github.com/DasKeyboard/q/blob/master/README.md.
