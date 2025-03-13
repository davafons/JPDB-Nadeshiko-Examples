# JPDB Immersion Kit Examples  

A Tampermonkey userscript for **jpdb.io** that embeds anime examples from **ImmersionKit** directly into the site.  

## Features  

- **Anime example images** displayed alongside vocab.  
- **Audio support** with autoplay and manual controls.  
- **Navigation arrows** to cycle through examples.  
- **Favorites system** to select preferred examples.  
- **Configurable settings** for appearance and behavior.  
- **Blacklist feature** to block unwanted examples.  

## Controls  

| Icon | Function |
|------|----------|
| 🔊 **Speaker** | Play example audio. |
| ⭐ **Star** | Mark as favorite (★ = favorite, ☆ = non-favorite). |
| 「」 **Exact Search** | Toggle exact search (「」 = enabled, 『』 = disabled). |
| ◀ **Left Arrow** | Go back one example. |
| ▶ **Right Arrow** | Go forward one example. |
| ☰ **Menu Button** | Open the settings menu. |

## Config Options  

The settings menu (**☰**) allows customization of the script's behavior:  

- **Image Width** – Adjust image size.  
- **Wide Mode** – Place image next to or above meanings.  
- **Definitions on Right in Wide Mode** – Place image left and definitions right.  
- **Arrow Width/Height** – Resize navigation arrows.  
- **Page Width** – Adjust overall layout width.  
- **Sound Volume** – Control audio playback volume.  
- **Enable Example Translation** – Show/hide English translation.  
- **Sentence Font Size** – Resize Japanese text.  
- **Translation Font Size** – Resize English translation.  
- **Colored Sentence Text** – Highlight vocab in the sentence.  
- **Auto Play Sound** – Automatically play audio when changing examples.  
- **Number of Preloads** – Set how many examples load in the background.  
- **Vocab Size** – Adjust vocab text size in reviews.  
- **Default to Exact Search** – Enables exact search option by default.  
- **Minimum Example Length** – Set a lower limit for sentence length.  
  - **⚠ Warning:** Changing this **will delete all current favorites.**  
- **Blacklist** – Prevent specific examples from appearing.  

## How It Works  

The script searches **ImmersionKit** for examples based on the current vocabulary and embeds them into **jpdb.io**. Audio can be played manually or automatically.  

### **Audio Playback Note**  
If autoplay doesn't work, check your browser's site settings (click the lock icon next to the URL) and allow automatic audio playback.  

## Favorite System  

Favorites allow you to pick a default example for a word. Next time the word appears, your chosen example will be used.  

## Links  

- 📜 **GitHub Repository:** [https://github.com/AwooDesu/JPDB-Immersion-Kit-Examples](https://github.com/AwooDesu/JPDB-Immersion-Kit-Examples)  
- 📥 **Download at Greasyfork:** [https://greasyfork.org/en/scripts/507408-jpdb-immersion-kit-examples](https://greasyfork.org/en/scripts/507408-jpdb-immersion-kit-examples)  
- 🛠 **JPDB Website:** [https://jpdb.io](https://jpdb.io)  
- 🎞 **ImmersionKit:** [https://immersionkit.com](https://immersionkit.com)  

## Contributing  

Contributions are welcome! If you encounter bugs, have feature suggestions, or want to improve the script, feel free to open an issue or submit a pull request on **GitHub**.  

## License  

This project is licensed under the **MIT License**.  

