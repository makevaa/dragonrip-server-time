# dragonrip-server-time

🐵 Tampermonkey userscript to show a server time clock for the browser game [Dragonrip](https://dragonrip.com/).
The time element is inserted at the bottom of the game logo box.

🍴 Available on GreasyFork: [greasyfork.org/en/scripts/533554-dragonrip-server-time](https://greasyfork.org/en/scripts/533554-dragonrip-server-time)


## 🛠 Settings
The <code>settings</code> object has properties to customize the clock:
- <code>clockLabel</code>: label to show before the time ("Server time" on default)
- <code>runningClock</code>: keep updating the clock even when page is not reloaded (updates once/sec)
- <code>enableSeconds</code>: show seconds in the time, otherwise only hours and minutes are shown
- <code>use24HourClock</code>: use 24h clock, 12h is used on default
- <code>fancyBox</code>: use some additioal CSS styling for the time element

## 💎 Preview
![Dragonrip Server Time 24h preview](https://i.imgur.com/DDSzLCj.png "Dragonrip Server Time 24h preview")

![Dragonrip Server Time 12h preview](https://i.imgur.com/20rScQS.png "Dragonrip Server Time 12h preview")






