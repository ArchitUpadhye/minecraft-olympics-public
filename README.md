# MC Olympics
A minecraft tournament run by myself coded fully using datapacks and in-built game mechanics to create a scored event across 8 games and a finale game. From Mario-Kart-style racing mechanics to one-hit shooter games, from bleep tests to multipliers which increase game points as the event moves on, making later games more crucial. This event has ran since 2024 and has required event organisation, teamwork, communication and resilience across countless rounds of testing to ensure the event is robust for event day.
---
# Games include:
* Biathlon - a 3 lap racing game around a track with obstacles, speed boosts and jump pads to encourage dynamic movement from players.
* Boxing - 3 rounds on an island above void, scoring points for survival and kills.
* Battleships - each team has a round to hide ships in a map; points awarded for finding ships, your ships surviving and eliminating other players.
* Spleef - a minecraft classic, except there is decay towards the end of the game, to separate the best from the best.
* Item Rush v1 - a set of 9 items is given to each team to race to see who finishes first yet PvP randomly turns on to ensure players are wary of their surroundings.
* Item Rush v2 - over 500 items have been coded into the game which randomly are assigned to teams to gather and the most wins.
* Parkour Party - a series of parkour race courses like parkour within a team, a bleep test and a course with checkpoints.
* Race of Hearts - based on a server called Lifesteal, killing someone gains you a heart and everyone is one-shot. You can also mine blocks of your colour around the map and place in the centre to secure further points.
* Obstacles - a spin-off of Parkour Party; 3 rounds with a bridging round, nautilus racing and a Floor is Lava round where lava rises every few seconds.
* Escape Room - a dynamic escape room full of challenges like word puzzles and teamwork, which has lots of coded sensors to detect when each part has been completed.
* Tower Capture - a simple capture the point game where each team goes up against another in a round robin.
* Ore Scrambling v1 - mine ores then parkour on ores, e.g. if you mine 2 iron ore you can only jump on 2 iron ore.
* Ore Scrambling v2 - like v1, but the jumping phase is made more difficult with a bleep test mechanic and a randomly changing floorboard.
* Prop Hunt - finale game where top 2 teams play for the win. The team that gets 1st chooses to hide or hunt first. Hiding teams must survive the time without getting shot (they are one-shot) and hunting teams must catch all players within the round. First to 3.
> _"I spent a lot of the pandemic watching minecraft events and always wanted to play in them, so I decided to combine my passion for coding with my love for events to design my own event with unique minigames."_
# Other inclusions:
* Event Breakdown  
  1. Voting - a voting system where players can vote for their desired game, and if there is a tie, a random one is picked.
  2. Multiplier - System which increases points' worth after each game
  3. Running Timer - a timer runs throughout the event to show how long is left in each game, and show voting/intermission timers. The timer can also be paused and unpaused in case contestants need toilet breaks or have emergencies.
* Automatic Scoring
  1. Team Based - this is scored on the sidebar for each game throughout the event, and the overall team leaderboard is displayed between games.
  2. Individual - using the tab feature, individual placements and opints are clear to show the make-up of the team's constitutent points.
## Author's Note
There are 8 games which all teams play and they will earn points in each game which is shown on screen to all players dynamically using a leaderboard feature. Later games are worth more points by using a multiplier and players can vote for each game during a voting period. If there is a tie, a random game is chosen. The top two teams play the finale game: Prop Hunt, and the winner of this game will win the event and make it to the gold podium.
There have been many issues over the years when developing and programming this event; as a result, I have learnt to have a keen eye for attention to detail and have written out all programs in pseudocode before carrying out the real thing. An issue I encountered in Item Rush v2, is that since each team will have different items at one point, I will need to show a different dynamic scoreboard for each team which required me to make a scoreboard for each team.
This was tested solo and with multiple competitors prior to each event to minimise errors during real events. Originally, there were just 6 players, which isn’t a lot, but now has run multiple events with 12 players, with aspirations to move onto 15. The event has allowed me to improve my organisation and coordination and player management is also important to sure there are no conflicts within teams.
On the coding front, there have been lag-based issues on the server due to having not tested with the same number of players in the event. There have also been some issues which have occurred due to invalid tags for players from previous events which has resulted in invalid player selection within code. Hence, further quality control could eradicate any logic errors.
### Inspirations
[MC Championship](https://www.bing.com/ck/a?!&&p=02a92fd4e74d57ae17502f140c87afec7b54eae14a1567a66dee7ae05ba6c558JmltdHM9MTc4OTM0NDAwMA&ptn=3&ver=2&hsh=4&fclid=181f50fa-cc47-65d6-061e-472ecd6264d6&psq=mc+championship&u=a1aHR0cHM6Ly9tY2NoYW1waW9uc2hpcC5mYW5kb20uY29tL3dpa2kvTUNfQ2hhbXBpb25zaGlw)  
[Block Wars](https://www.bing.com/ck/a?!&&p=d2592eac06c86c0f6077f5a038d6e9acb7feac503db8fabafc42970679f1d7b5JmltdHM9MTc4OTM0NDAwMA&ptn=3&ver=2&hsh=4&fclid=181f50fa-cc47-65d6-061e-472ecd6264d6psq=block+wars&u=a1aHR0cHM6Ly9ibG9ja3dhcnMuZ2FtZXMv)  
[Pandora's Box](https://www.bing.com/ck/a?!&&p=de53243ef36f3bb9b44ecef828c160b7f323d0851edd5f83aad2389f192565a2JmltdHM9MTc4OTM0NDAwMA&ptn=3&ver=2&hsh=4&fclid=181f50fa-cc47-65d6-061e-472ecd6264d6&psq=pandoras+box+evnet&u=a1aHR0cHM6Ly9wYW5kb3Jhcy1ib3gtZXZlbnQuZmFuZG9tLmNvbS93aWtpL1BhbmRvcmElMjdzX0JveF9FdmVudF9XaWtp)
