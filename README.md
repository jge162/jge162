<div style="display: flex;">
<p align="left"> 
  <img src="https://komarev.com/ghpvc/?username=jge162&label=Profile%20views&color=0e75b6&style=flat" alt="jge162" /> 
</p><img src="https://img.shields.io/github/stars/jge162?style=social" alt="GitHub User's stars">
  <a href="https://github.com/jge162?tab=followers"><img src="https://img.shields.io/github/followers/jge162?label=Followers&style=social" alt="GitHub Badge"></a>
</div><br>

```python
#!/usr/bin/env python3

import datetime
import random

def welcome_message():
    """
    Print a welcome message with dynamic elements.
    """

    # Dynamic date
    today = datetime.datetime.now().strftime("%Y-%m-%d")

    # Random welcome phrases
    welcome_phrases = [
        "Welcome to my digital abode!",
        "Glad to see you here!",
        "Welcome aboard, fellow coder!",
        "Hello and welcome!"
    ]

    messages = [
        "-----------------------------------",
        "B.S., Computer & Electronics Engineer",
        "M.S., Computer Science (Cybersecurity) '24",
        "PhD after MS? maybe IDK",
        "Welcome to my GitHub repository!",
        "Feel free to look around.",
        "Contributions are welcome!",
        "-----------------------------------",
        f"Today's Date: {today}",
        random.choice(welcome_phrases),
        "-----------------------------------"
    ]

    for message in messages:
        print(message)

if __name__ == "__main__":
    welcome_message()

```
