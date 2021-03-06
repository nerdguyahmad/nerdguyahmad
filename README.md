<div>
  <p align="center">
    <img src=https://shields.io/badge/Skill-Python_(Decent)-blue>
    <img src=https://shields.io/badge/Skill-Javascript_(Intermediate)-yellow>
    <img src=https://shields.io/badge/Skill-Web_Developer_(Intermediate)-green>
    <img src=https://shields.io/badge/Skill-C++_(Novice)-purple>
    <br>
    <img src=https://shields.io/badge/Achievement-Discord_Verified_Bot_Developer-blue>
    <br>
    <img src=https://shields.io/badge/Current_Status-Available-success>
  </p>
  <h1 align="center">I :heart: code.</h3>
  <p align="center"><strong><q><i>Testing leads to failure, and failure leads to understanding.</q></strong> - Burt Rutan</i></h3>
</div>

## 💁 About Me
Hi, I'm Ahmad. I go by He/Him. I'm 14 and I'm just a casual python developer who likes to make useful stuff. I'm decent in discord.py and like to code discord bots. Oh and I'm a discord enthuasist.

## 💼 Projects
Here are some of my (current) projects I'm working on

### 🔐 Closed source
- [WEEBOT](https://dsc.gg/weebot) (Verified Discord Bot) - (Discontinued as of 10th June 2021)
- [Util](https://dsc.gg/util) (Discord Bot) - A feature rich server utility discord bot.

### 📖 Open source
- [Starbot](https://github.com/nerdguyahmad/starbot) (Discord bot) - A feature rich and powerful starboards managing discord bot.

## 👀 Looking for contribute
I'm currently looking to contribute in Discord bots and relevant projects.

## 💬 Contact
Please contact me on Discord if you want quick replies. However, My contact email is also available.

<div id="contact">
  <a href="https://dsc.bio/nga">
    <img src="https://static.wikia.nocookie.net/sanicman/images/c/ca/Concours-discord-cartes-voeux-fortnite-france-6.png/revision/latest?cb=20191015023221" width="40" height="40">
  <a href="https://instagram.com/nerdguyahmad">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Instagram_logo_2016.svg/768px-Instagram_logo_2016.svg.png" width="40" height="40">
  </a>
  <a href="mailto@nerdguyahmad.contact@gmail.com">
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Mail_%28iOS%29.svg" width="40" height="40">
  </a>
</div>

## ⌨️ SRC
```py
import requests

class Profile:
  """My GitHub Profile"""
  def __init__(self):
    self.name = "Izhar Ahmad"
    self.age = 14
    self.pronouns = ["He", "Him"]
    self.location = "Pakistan"
    self.favorite_language = "Python"
    self.favorite_library = "discord.py"    
    self.hobbies = ["Gaming", "Making useful stuff", "Discord bot development"]
    
    repos = requests.get("https://api.github.com/users/nerdguyahmad/repos").json()
    self.open_source_projects = [repo['fullname'] for repo in repos if not repo['fork']]
    self.closed_source_projects = ["WEEBOT", "Util"]
    
    self.contact = {
        "discord": {
            "response": "fast",
            "username": "nerdguyahmad#3195"
          },
        "email": {
            "response": "slow",
            "username": "nerdguyahmad.contact@gmail.com"
          },
       "instagram": {
          "response": "medium",
          "username": "nerdguyahmad"
        }
      }
```
