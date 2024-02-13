![banner](https://discord-extensions.github.io/assets/banners/compact-userarea.png)

---
### ![betterdiscord](https://discord-extensions.github.io/assets/icons/betterdiscord.png) **[BetterDiscord](https://betterdiscord.app)**
Download information coming soon:tm:. Attempting to get it published on the site before I provide anything.

### ![vencord](https://discord-extensions.github.io/assets/icons/vencord.gif) **[Vencord](https://github.com/Vendicated/Vencord)**
#### From URL
1. Go to user settings (CTRL + ,)
2. Go to the "Vencord" category in user settings (CTRL + ,), select the "Themes" tab, then select "Online Themes".
3. In the input field under "ONLINE THEMES" paste the following URL (if you have some here already, add a comma before the url).
```
https://discord-extensions.github.io/compact-userarea/src/source.css
```

### ![stylus](https://discord-extensions.github.io/assets/icons/stylus.png) **Stylus**
1. Install the broswer extensions for your repsective browser.
    - [Chrome Webstore](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
    - [Firefox Addons](https://addons.mozilla.org/en-US/firefox/addon/styl-us)
2. Once installed, open [this link](https://discord-extensions.github.io/compact-userea/clients/compact-userea.user.css) in a new browser tab. This opens the page where you will install this userstyle.
3. Press the `Install Style` button.

---

### Why is the avatar low quality?
Discord uses a 32x32 image for the userarea avatar. Since it's being resized to 48x48, it looks low quality because it's not the correct size for the image. If this is something that constantly bothers you, there is an override variable that you can provide a url to. Note that you will have to update it everytime you update your avatar, but this is the best possible fix I have for it.
```css
:root {
    --avatar-source-override: url('YOUR_AVATAR_URL');
}
```

### Where is my avatar decoration?
Avatar decorations will not display for the time being. I do have a way to upscale all of them to look correct, however I need a URL to every single avatar decoration. Expect this in a future update.

---

### License
This theme is licensed under the MIT license. Please refer to the [LICENSE](./LICENSE) file for more details regarding rigths and limitations.

### Support
If you've ran into an issue with an area being unthemed, **PLEASE REPORT IT IN AN ISSUE**. If you have some other issue you need help with, feel free to join my [support server](https://discord.gg/vYdXbEzqDs).