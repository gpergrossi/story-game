# Story Game

### What is it?
It is a REST API for multiple users to connect, form parties,
and play through choose-your-own-adventure content together.
Decisions will be put to a vote. Tie breakers can trigger
special plot events. The players can get separated and play
through plot lines in smaller groups or alone.

### Plans
In this section I will keep note about currently planned features

#### Basic Functionality
[ ] Single user can connect, choose a name, and read through a story, no choices.
[ ] Single user choice system and a single fork in the story.
[ ] Multiple users connect. Synchronization points where you wait for everyone to continue.
[ ] Multiplayer choices resolved by vote.
[ ] Add custom tie breaker event to the story and implement supporting code.

#### World Building
[ ] Locations. Track where players are and control what they're allowed to do in those places.
[ ] Items. Track what players have and what they can do with those things.
[ ] Inventory. Track where player's items are stored / equipped. Control events based on equipment, or have the player lose their bag + items stored in it.
[ ] Characters. Track characters' (and players') personal details. Name, professions, hobbies, back story, treasured memories, character flaws, etc.

#### Game Mechanics
[ ] Statistics. Assign and read stats to/from and person. Virtual stats can perform math based on other stats. Control available plot options based on stats.
[ ] Rolling. Implement dice rolling based on stats for certain decision outcomes.
[ ] Combat. Implement a combat system that can run a combat encounter using peoples' stats.
[ ] Status Effects. Implement temporary effects that tick at specified times in combat or out of combat.

#### Extra Details
[ ] Five Senses. Standardize object descriptions so they can be queried specifically for smell, taste, appearance, sound, and feel.
[ ] Event System. Trigger events for most actions. e.g. When an item is picked up, when ap layer enters a location, when a word is spoken, etc.

