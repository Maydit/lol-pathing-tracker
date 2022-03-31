# lol-pathing-tracker
Determine a player's likely position based on information from the minimap in league of legends using CV and ML techniques

Roadmap:

- [ ] Gather data of minimaps of various sizes and champions redorded with fog of war on red, blue, both.
- [ ] Ensure that position detection correctly works (when a champion is shown it is 100% accurate)
- [ ] Going to use https://github.com/farzaa/DeepLeague for champion location detection
- [ ] Additional data like rank, in game time, dragon soul, server region?
- [ ] Attempt to use NLP method of replacing champ positions with <MASK>
- [ ] Determine a baseline accuracy with no prediction
- [ ] Real time screen reading?
