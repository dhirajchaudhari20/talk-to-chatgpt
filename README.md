# Talk-to-ChatGPT

**Talk-to-ChatGPT** is a Google Chrome and Microsoft Edge extension that allows users to talk with the ChatGPT AI using their voice (speech recognition) and listen to the bot's answer with a voice (text-to-speech), rather than just by typing. With this tool, users can speak to the AI and receive spoken responses, making the interaction feel more natural and conversational. This allows you to have your own personal assistant in the style of Iron Man's Jarvis, which is fun, but it's also a great way to help the elderly and people with disabilities interact with ChatGPT. **We now support ElevenLabs API integration, which means you can create your own voices for text-to-speech!**

The extension can be downloaded from here:
- From the **Chrome Web store** here: [Download from Chrome Web Store](https://chrome.google.com/webstore/detail/talk-to-chatgpt/hodadfhfagpiemkeoliaelelfbboamlk)
- From the **Edge Web store** here: [Download from Edge Web Store](https://microsoftedge.microsoft.com/addons/detail/talktochatgpt/bkkdkngklccknmoalpoakglipbibafpn)
- Manual installation option, detailed further below

After installing the extension, open or reload the ChatGPT page ([https://chat.openai.com/](https://chat.openai.com/)) and you should be seeing a 'Start' button on the top right corner of the page. After you click Start, you will be asked for permission to use your Microphone. This is required to enable voice recognition.

![Talk-to-GPT Widget](/images/260-main.png?raw=true "Talk-to-ChatGPT Widget")

Once started, Talk-to-ChatGPT displays a menu on the top right corner of the page where users can access settings (such as voice, language, and more), skip the current message, toggle voice recognition on or off, and toggle text-to-speech on or off.

The settings menu can be seen below. Settings are saved in a cookie and reloaded automatically each time you activate the script.

![Talk-to-GPT Settings 1](/images/260-settings-1.png?raw=true "Talk-to-ChatGPT Settings 1")

![Talk-to-GPT Settings 2](/images/260-settings-2.png?raw=true "Talk-to-ChatGPT Settings 2")

Demo V2.6 with ElevenLabs support: [Watch on YouTube](https://www.youtube.com/watch?v=gnijfWuenKA)

## How to install

### Option 1: CHROME or EDGE STORE
- Google Chrome: download from the Chrome extension store at [Download from Chrome Web Store](https://chrome.google.com/webstore/detail/talk-to-chatgpt/hodadfhfagpiemkeoliaelelfbboamlk) 
- Microsoft Edge: download from the Edge extension store at [Download from Edge Web Store](https://microsoftedge.microsoft.com/addons/detail/talktochatgpt/bkkdkngklccknmoalpoakglipbibafpn)

### Option 2: MANUAL INSTALL
If the extension is temporarily unavailable (this can happen when OpenAI make breaking changes), or if you want to install the latest updates before they are available on the Chrome/Edge web store, you can install the extension manually. Here is how you do it.
1. Download the .zip file here: [Download Zip File](https://github.com/C-Nedelcu/talk-to-chatgpt/raw/main/chrome-extension/chrome-extension.zip) (this link will always point to the latest version)
2. Extract the .zip file in a folder somewhere
3. Follow this tutorial to install the extension in Chrome/Edge in dev mode: [Tutorial](https://webkul.com/blog/how-to-install-the-unpacked-extension-in-chrome/)

## FAQ

**Q: Which web browsers are supported?**  
A: This extension is designed for Google Chrome and Microsoft Edge, desktop version only. The extension will not work in any other web browser, especially not mobile browsers, because these browsers do not support the necessary APIs for speech recognition and speech synthesis.

**Q: Can you make it speak faster or in a different voice or language?**  
A: Yes, use the settings menu. You can select a variety of settings among which the speech rate, voice type, and language.

**Q: What is the purpose of this project?**  
A: Originally, it was mostly a fun proof of concept. This AI is mind-bogglingly intelligent and I had a deep desire to converse with it orally, to make it more interesting. Surely OpenAI themselves will make a proper voice-controlled version of ChatGPT in the future, at which point my project will be rendered useless. For now, it seems to be helping people with disabilities / visually impaired people, so I'm going to be actively working on the project for as long as I can, as a form of contribution to society.

**Q: Is it safe to use?**  
A: Yes, it's simple javascript code that will execute only in the context of the ChatGPT webpage. It doesn't request any particular permissions, and it is fully open source. As soon as you navigate away from ChatGPT, everything is cleared, except for the addon settings.

**Q: Will it always work?**  
A: it might not work indefinitely, and here's why. The code is based on the current HTML structure of the ChatGPT page. If OpenAI change the HTML code, this project will likely stop working. I will probably keep updating it to maintain compatibility, but I'm not sure I'll be doing that forever. If you want to contribute to the project you are more than welcome to submit your own changes through Github.

**Q: I have an error or a problem...**  
A: Feel free to update the javascript yourself and propose changes on Github, or simply report the issue if you aren't a programmer.

**Q: Can I make changes to your code?**  
A: Yes, feel free to make changes, and do whatever you want, commit, fork, just have fun.

**Q: How do I know what languages are supported?**  
A: this is entirely based on the web browser APIs (Google Chrome, Microsoft Edge), so you need to ask Google or Microsoft, as I cannot provide an up-to-date answer. I've only tested it with English, French, and Chinese. The languages in the settings menu are the same ones found on the Google and Edge demos.



## Donations

Thanks for reading all the way down. Are you enjoying Talk-To-ChatGPT and want me to continue improving it? You can help by making a donation to the project. Please click the Donate button to proceed.



Created by Dhiraj Chaudhari. [LinkedIn Profile](https://www.linkedin.com/in/dhiraj-chaudhari-06ba10259/)
