# Lavender

A good looking dark purple-ish theme for discord.

## Support

For bug reports open a issue here on github with the provided templates.

For problems installing or using the theme join our [server](discord.gg/B9TK7nqRE4) and ask for help.

# Installation

### [Powercord](https://powercord.dev/)

- **Step 1:** Open **Command Prompt / Terminal / Powershell**
- **Step 2:** Paste the below code in your terminal:

```bash
cd powercord/src/Powercord/themes && git clone https://github.com/Obscure-Git/Lavender
cd %homepath%
```

### [BetterDiscord](https://betterdiscord.app/)

- **Step 1:** Go to clients folder on this repo.
- **Step 2:** Download the `lavender.theme.css` file.
- **Step 3:** Paste the downloaded file inside your BetterDiscord themes folder.

### [GooseMod](https://goosemod.com/)

**Coming soon!**

### [Vizality](https://vizality.com/)

- **Step 1:** Open your themes folder.

- **Step 2:** Open a **Command Prompt / Terminal / Powershell** window there and paste the below code:

  ```bash
  git clone https://github.com/Obscure-Git/Lavender
  ```

### Browser / Web

1. Install the **Stylus** extension for [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) / [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) / [Opera](https://github.com/openstyles/stylus/wiki/Opera,-Outdated-Stylus).

2. After installing, head over to [this link](https://obscure-git.github.io/Lavender/clients/lavender.user.css).

3. Press the "**Install Style**" button.

# Important

When scrolling through member lists and long channel lists, the scrollbar randomly gets stuck and starts flickering. To get rid of this annoyance you can try the below fixes:

## Fix 1

Fix 1 is by downloading a plugin called [SmoothScrollPowercord](https://github.com/LynithDev/SmoothScrollPowerCord).

## Fix 2

Fix 2 is by unloading a part of the theme, this will make the channel list and members list a little ugly so only use this if Fix 1 doesn't work for you.

- **Step 1:** Go to `src` folder and open the `source.scss` file.

- **Step 2:** Inside `source.scss` file remove/comment out every line that starts with: `@use "lists/`

You might need to repeat this thing sometimes when you update the theme.

# Credits

Lavender uses snippets from many other theme devs, all the snippets are either in `/addons` folder or in snippets file in `src/base/snippets.css` with credits to the respective devs. (Contact me in my [server](discord.gg/B9TK7nqRE4) if I have forgotten or mistaken with any credits 👍)

## Concept

Lavender was inspired by a dashboard concept from dribble, made by [SajjadMohammadiNia](https://dribbble.com/SajjadMohammadiNia) for [Piqo Design](https://dribbble.com/Piqodesign).

### The original concept looked like: 
<img src="https://cdn.dribbble.com/users/1787150/screenshots/15137908/media/cf05e3a31b0c9f17336349e08d223815.png?compress=1&resize=1200x900&vertical=top" alt="Concept Image">

# Previews

Note: Screenshots might be outdated because I only update them like once a week and sometimes I forget 😬.

### Theme
<img src="./assets/1.png" alt="screenshot1">

### User Popouts
<img src="./assets/2.png" alt="user-popout">

### User action buttons
<img src="./assets/3.png" alt="user-action-buttons"><img src="./assets/3-gat.png" alt="user-action-buttons-with-game-activity-toggle-button">



### Status Indicators

<img src="./assets/4b.png" alt="Status Indicators">
<img src="./assets/4a.png" alt="Status Indicators">

### Powercord Spotify Module

<img src="./assets/5.gif" alt="Powercord Spotify Module">