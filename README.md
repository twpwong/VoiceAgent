# VoiceAgent

### Introduction:

An important part of working at Assort will be scrappiness and the ability to build out and hack at things 0→ 1 with whatever resources you need as you would if you were to work with us. Please do not copy someone else’s code or repo completely though. Please do not use Vapi. The goal of this assignment is for you have fun with what we believe is an interesting project and test your ability to work with open source to build a live product in a short amount of time. 

*Note: Please share all deliverables outlined at the bottom once finished*

### Resources:

AI agent frameworks to checkout and use:

- https://docs.livekit.io/agents/voice-agent/
- https://github.com/pipecat-ai/pipecat

TTS:

- https://docs.elevenlabs.io/api-reference/quick-start/introduction
- https://docs.cartesia.ai/getting-started/welcome

STT:

- https://deepgram.com/product/speech-to-text
- https://www.assemblyai.com/products/speech-to-text

Telephony system/Hosting Phone number:

- https://www.twilio.com/en-us

We prefer if you code this in Python as that is what you’ll primarily be working in at Assort, but feel free to use the language of your choice!

### Assignment:

Using resources above, or whatever else you find, produce a working demo (number that we can call), that connects the caller with an AI agent which will:

- Collect patient's name and date of birth
- Collect insurance information
    - Payer name and ID
- Ask if they have a referral, and to which physician
- Collect chief medical complaint/reason they are coming in
- Collect other demographics like address
    - For the address, please notify the user if the address is invalid or missing other fields by using an external validation API
- Collect contact information: phone number and optionally email
- Offer up best available providers and times
    - Feel free to use fake data and make up doctors and times

The call should not be considered resolved until these pieces of information are all received. After the call ends, send emails to the potential callers (jeff@assorthealth.com, connor@assorthealth.com, cole@assorthealth.com, jciminelli@assorthealth.com, akumar@assorthealth.com, riley@assorthealth.com) that informs them of their selected appointment date and time, and which doctor they will be seeing.

### Deliverables:

1. Share your GitHub repo of work you’ve done - Please ‘share’ access to your GitHub repo to the following emails, and copy/paste the URL in an email to riley@assorthealth.com
    - Please make it private and share with:
        - https://github.com/jeffery300
        - connor@assorthealth.com
        - cole@assorthealth.com
        - jciminelli@assorthealth.com
2. Hosted phone number which we can call at any time to experience the agent live which you’ve built

Good luck and have fun!

### **FAQs:**

Q: How can I make sure someone from Assort can call in and test?

A: You may need to register our number in order to let us make calls to your agent using the Twilio free account. Please sync with Riley to do this by sending a 2FA code to [(972) 974-0709](tel:9729740709). Riley will need to get you back the code within 10 minutes, so it may also be helpful to give her some advance notice.