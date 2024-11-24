# 🛠️ CCAI Telephony Assessment

---

## Question 1  
**Which of the following advanced speech settings is most impactful to the performance of your solution?**  
- ❌ Barge-in  
- ✅ **Speech model**  
- ❌ Advanced timeout-based endpointing  
- ❌ End of speech sensitivity  

---

## Question 2  
**Which of the following are returned from the CCAI APIs through the telephony integration’s gRPC? (Choose three)**  
- ❌ The caller’s geolocation  
- ❌ The caller’s IP Address  
- ❌ The caller’s audio stream**  
- ✅ **Programmatic events that change the conversation state**  
- ✅ **Session parameters**  
- ✅ **Start of speech detection**

---

## Question 3  
**Your virtual agent has trouble understanding users. When you check Dialogflow conversation history, the transcripts do not match what the user said. You enable Dialogflow’s audio export bucket to record some calls that exhibit the issue and notice the speech is clear and understandable. How might you fix this?**  
- ✅ **Specify manual speech adaptations for the phrases I want to transcribe correctly.**  
- ✅ **Check that auto speech adaptation is enabled, then make sure the agent’s training phrases and entities contain the phrases the users are actually saying.**  
- ✅ **Configure a different Google speech model better suited for my use-case.**  
- ❌ Be patient. Google models will eventually adapt to my users’ speech and my use-case.  
- ✅ **Enable call companions to offer users an alternative input method.**  
- ❌ There’s nothing I can do without implementing my own speech recognition.  
- ✅ **Ensure that I collect alpha/numeric sequences (like 12345678 or ABCD1234) through form-filling.**
---

## Question 4  
**Which of the following are sent through telephony integration’s gRPC to the CCAI APIs? (Choose three)**  
- ✅ **Programmatic events that change the conversation state**  
- ✅ **The caller’s audio stream**  
- ✅ **Session parameters**  
- ❌ The caller’s geolocation  
- ❌ Start of speech detection  
- ❌ End of speech detection  

---

## Question 5  
**Built-in Dialogflow features like barge-in, speech adaptation, and partial responses ensure consistent experiences regardless of your integration method.**  
- ❌ True  
- ✅ **False**  

---

## Question 6  
**When you test your virtual agent through your telephony integration, you experience long periods of silence before hearing a response to your inputs. How might you fix this? (Choose four)**  
- ✅ **Check the performance of my fulfillments’ webhooks.**  
- ✅ **Contact my integration owner for troubleshooting any networking or other processing issues.**  
- ❌ Enable advanced timeout-based endpointing and decrease the sensitivity slider.  
- ✅ **Specify a different speech model.**  
- ❌ My integration offers an option to specify the maximum number of seconds to wait after a user speaks.
- ✅ **Enable advanced timeout-based endpointing and increase the sensitivity slider.**  

---

## Question 7  
**You need at least one conversation profile per: (Choose three)**  
- ❌ Human Agent  
- ❌ Release version  
- ❌ Session  
- ✅ **Dialogflow agent**  
- ✅ **Unique Agent Assist feature combination**  
- ✅ **Language**  

---

## Question 8  
**Which of the following features could help reliably authenticate users to your virtual agent? (Choose three)**  
- ✅ **I can use a regexp entity and collect an alpha/numeric ID with required form-filling.**  
- ✅ **I can lookup known users from Caller ID then use Speaker ID to tell me which one is speaking.**  
- ✅ **I can cross-reference Caller ID with a DTMF-collected pin code.**  
- ❌ Speaker ID tells me which one of my many enrolled users is speaking.  
- ❌ I can use a regexp entity and collect an alpha/numeric ID by annotating the entity in intent training phrases.  

---

## Question 9  
**Google support asks you to share an audio recording of a problem behavior you’ve reported with your telephony experience. Which of the following considerations should you take? (Choose two)**  
- ❌ Test in the Dialogflow console and record your screen and mic.  
- ❌ Record your call from an app on your phone to get the original audio source.  
- ❌ Encode as MP3 files so they can be shared with support more easily.  
- ✅ **Check that the caller and agent audio are in separate files, or separate channels of a stereo audio.**  
- ✅ **Record calls from your CCAI contact center solution.**  
