# Ziggy PHP Voicebot - Llama3-70b and Groq
A php voicebot powered by Llama3-70b and Groq.

You can communicate with Ziggy using either your voice or text. Ziggy will respond with both voice and text. Yes, it's like Jarvis.

This project demonstrates a simple and cheap way to create a personal voicebot using only HTML, CSS and Javascript.

<br>

You can try this PHP voicebot here:<br>
(Please use the Chrome browser. This will only be live for a limited time.)<br>
https://ziggy.voicebot.woza.work/


<br>

## Javascript Voicebot
A Javascript voicebot is available here:<br>
(This repo also includes a detailed writeup)<br>
https://github.com/vbookshelf/Khuluma-Javascript-Voicebot-ChatGPT

<br>

## Revision History

Version 2.0<br>
1-May-2024<br>
1- Replaced ChatGPT with Llama3-70b running on Groq.<br>
2- Removed csv file saving and loading.<br>


Version 1.1<br>
25-May-2023<br>
1- Added code to save a chat as a csv file.<br>
2- Added code to load a saved chat as a csv file.<br>
3- Building in these features adds complexity to the code because variables need to be moved<br>
between Javascript and PHP. If the saving and reloading features are not needed then v1.0<br>
is a more robust choice.

Version 1.0<br>
24-May-2023<br>
First release<br>
1- Basic setup that does not include the "Save chat" feature<br>
2- Voicechat works on Mac but it's unstable on Windows and Android.
