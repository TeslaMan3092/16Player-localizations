# 16Player Localizations

Thanks for deciding to help localize 16Player into your language.

To start, you will want to get a copy of the English localization [here](https://github.com/TeslaMan3092/16Player-localizations/blob/main/en.lproj/Localizable.strings). Then copy the entire file into a text editor of your choosing. 

The format of the ``.strings`` files is simple... the text in UPPERCASE should not be edited, as it is what 16Player looks at to know where that string should go. The text on the left, of the equal sign in "quotes", is what you should change. Keep the quotes and only change what's inside the quotes.

An example looks like this...
This is the English translation of Lock Screen in the ``.strings`` file;
```
LOCK_SCREEN = "Lock Screen";
```
If you were trying to translate this to French it would then look like this;
```
LOCK_SCREEN = "Ecran vérouillé";
```
It is a good idea to follow along in 16Player's settings as you translate. Another thing to keep in mind is to try to use a universal language and try not to make your translation specific to your dialect. 

Once you have completed translating, you contact me in the contact section of 16Player or [join my Discord server](https://discord.gg/9MnqevttA4) and send your localization file.

---
**Testing**
<br>
An easy way to test your localization is to copy and paste the file into the current used languages folder. Don't worry if you mess something up just reinstall 16Player from Chariz and it will go back to default. The path of the main folder is ``(your JBs root folder)/Library/Application Support/SixteenPlayerLocalization.bundle/(your current used language folder)``.
Once you are there open the ``.strings`` file and delete what's there then paste your new localization. Once you have done all that, make sure to kill the Settings app in the app switcher then re-open 16Player's settings and you should see 16Player's strings in your language.

---

# Credits

###### Thank you to the following people who helped localize 16Player into these languages. Also thanks to [Nightwind](https://github.com/NightwindDev/Jade-Localizations) for an example of how to structure this repo. 
- 🇨🇳 Chinese (Simplified) - [Gushi](https://twitter.com/Put_Story)
- 🇺🇸 English - [tesla_man](https://x.com/tesla_man3092)
- 🇹🇫 French (semi translation) - [rootfs](https://x.com/rootfsdev)
- 🇮🇩 indonesian - @sweetcysko (on discord)

