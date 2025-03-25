1.	Problem Statement:

We are all well aware about Cortana, Siri, Google Assistant and many other virtual assistants which are designed to aid the tasks of users in Windows, Android and iOS platforms. So in this project we worked on developing a virtual assistant using python for our PCs and Laptops.



2.	Introduction:

Nowadays the development of artificial intelligence (AI) systems that can organize a natural human-machine interaction (through voice, communication, gestures, facial expressions, etc.) are gaining popularity. One of the most studied and popular was the direction of interaction, based on the understanding of the machine by the natural human language. It is no longer a human who learns to communicate with a machine, but a machine learns to communicate with a human, exploring his actions, habits, behaviour and trying to become his personalized assistant.
Virtual assistants are software programs that help you ease your day to day tasks, such as showing weather reports, creating remainders, making shopping lists etc. They can take commands via text (online chatbots) or by voice. Voice-based intelligent assistants need an invoking word or wake word to activate the listener, followed by the command. We have so many virtual assistants, such as Apple’s Siri, Amazon’s Alexa and Microsoft’s Cortana.
This system is designed to be used efficiently on desktops. Personal assistants software improves user productivity by managing routine tasks of the user and by providing information from an online source to the user.
2.1.	Libraries Used
We used 6 python libraries to make our project -
a)	speech_recognition: Library for performing speech recognition

b)	pyttsx3: this is a text-to-speech conversion library in Python

c)	pywhatkit: this library is used for sending WhatsApp messages, playing YouTube videos, google search etc.

d)	datetime: this library gives date and time information

e)	wikipedia: this library searches things on Wikipedia and give us the results

f)	pyjokes: this library gives random jokes

2.2.	Structure of Program
We split our program into 3 functions-
a)	run_alexa(): this function calls take_command() function to take command and perform task according to the input received 
b)	take_command(): this function takes voice command from the user and returns the command to run_alexa() function
c)	talk(): this function uses text to speech library to convert the processed information into speech




3.	Practical Applications- what’s new/ problem solved
Virtual Assistants such as Amazon Alexa are vaguely popular these days. Anything we need is just a command away from us. But Alexa costs money therefore we tried replicating some its  features to give similar virtual assistant that is for free, all we have to do is call Alexa… Some of the features it supports are - communication using your voice, listen to your favourite songs, get current data and time, get information from Wikipedia, etc.

It’s very easy to operate our Alexa. We just need to say Alexa and then a command to get things done

For example :
•	"Alexa, play [artist/song/album name]." – This will play your preferred song or album or video from youtube
•	"Alexa, what's the time?"  - This will tell you present day date and time
•	"Alexa, who is (“person or any topic “)?" – This will search your answer from Wikipedia and deliver it to you.
So from these commnds we are now more clear on how to use our Alexa.

4.	Working Code with screen shots
Here is the program interface –
 

4.1.	Libraries Used
4.2.	Functions
4.2.1.	 talk()
This function uses text to speech library to convert the processed information into speech
  




4.2.2.	take_command()
This function takes voice command from the user and returns the command to run_alexa() function
 


4.2.3.	run_alexa()
This function calls take_command() function to take command and perform task according to the input received

