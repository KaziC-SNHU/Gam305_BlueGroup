# Game 305 Blue Team Design Document

Team Lead: Matthew C\
Head Level Designer: Carlos P\
Head UX Designer: Jon B\
Head Programmer: Matthew C\
Head Artist: Ruben G

# Gam 305 Blue Team Project Design Log
# Module Two Team Project Plan
Members Present: Matthew C, Carlos P, Ruben G, Jon B
## <ins>Brainstorming Scenario, Theme, and Additions</ins>
We opened our discussion with a decision on the main scenario. We decided on developing a fantasy-esque 3D sidescroller where the player is attempting to reach the end of the scenario through various obstacles.\
The player will have to utilize their available spells, navigate their environment, and solve simple puzzle to move through obstacles.\
These obstacles include enemies, hazards, moving hazards, small button puzzles, moving doors, and various other items.\
Additions we've officially decided on include the following:
- Player Pickups, Including but not necessarily limited to health, spell charges, and \[insert third here]
- Player Buff Collectibles that boost the player's stats such as maximum mana and new abilities
- Collectible objects that add to the player's score (just for fun)
- Enemies that move or fly based on their type, dealing damage to the player and providing a target for spells
- Objects and Hazards that sometimes move to cause the player to think on their feet and provide interest and challenge to the game\
~~Apparrently just all of the additions~~

## <ins>Timeline</ins>
Week 6 is the due date for what is essentially the final version of the game. Backtracking from there, week 5 is the due date for the beta, and week 4 is the due date for the alpha.\
Our timeframe, as denoted in our [Traceability Matrix & Test Plan](https://docs.google.com/spreadsheets/d/1SxsREcejOCHreUQ_BOJgph043edeALFdYJSkJ14a3J0/edit?gid=1693832793#gid=1693832793) document, will abide by this,
and all features listed for each stage of release will be completed to the best of our abilities.

## <ins>Alpha Stage</ins>
Alpha stage is planned to include a basic level blockout, essential controls for the player character and camera, one usable spell, at least one enemy, and a few collectibles.

## <ins>Beta Stage</ins>
The Beta Stage is planned to include essentially the entirety, or most of, the playable game. This includes, but is not necessarily limited to, developed levels, obstacles, enemies, collectibles,
a minimum of three spells, fleshed out pickups, and anything else that is required for the game submission.

## <ins>Communication</ins>
Preferred communication method may change as required, but for the moment we are present in the class discord through text and voice chat.\
In addition, the Test Plan document exists for required information, and emails are available.\
Communication will happen as frequently as is possible and necessary, especially when communicating about tasks or discussions such as this.\
The goal is to meet at least three times a week to discuss project work as well as to make general progress, but more or less meetings may occur as necessary.\
Task assignments are handled through the aforementioned [Traceability Matrix & Test Plan](https://docs.google.com/spreadsheets/d/1SxsREcejOCHreUQ_BOJgph043edeALFdYJSkJ14a3J0/edit?gid=1693832793#gid=1693832793) document.


# Module Three Project Log - Team Development: QA and Testing Plan
Members Present: Matthew C, Carlos P, Ruben G, Jon B
## Test Planning
Our testplanning includes a page in our Traceability matrix document including reports, dates, checklists, and the function tested.
This also is a place for recording bugs, resolutions, and changes regarding the aforementioned bugs.
We regularly test work done by ourselves or other developers as well, conferring about it in text or voice chats.
This regular testing is currently primarily focused on our pre-production phase work (the pre-alpha).
However, this also applies to when we move to our demo: Regular tests will be conducted on features as they come along,
and just as well major tests will be done on playability and the 'vibe' of the game once a week. This is especially important before major releases or submissions.

# Module Four Project Log - Team Reflection
Members Present: Matthew C, Carlos P, Ruben G, Jon B
## The Testing Process
The testing process was efficient, with no real issues. Any bugs were resolved as the item was being implemented into the game, so the only real testing needed was to get the general "vibe" of everything put together.\
Bugs were identified through intermittent testing during production, noted in the discord or on the google sheet, and then resolved either alone or with group effort.\
The only thing that could be done to improve the testing process is better maintaining the testing plan, which is something that should be practiced.\
The only tools the team utilized were Unreal Engine 5, GitHub, and our google sheet and Discord for communication. These tools were all either absolutely essentially or incredibly helpful.\
The team did not find any tools unhelpful or counterproductive.\
The team's approach to the game design document promoted, due to its simplicity, a simple approach and thus motivated us to use few tools, only accessing what we needed in order to be successful.
This approach seems to be working efficiently thus far, and keeps the bloat down on how many things each member is managing.

# Module Five Project Log - Team Reflection
Members Present: Matthew C, Carlos P, Ruben G, Jon B
## Beta Post Mortem
This evolution of our game went rather smoothly. All group members did our parts and the workflow was as smooth as could be. There were a couple of hiccups--Unreal Engine decided to corrupt our map, player, and HUD files for some reason,
but this was quickly resolved by simply extracting the files of a previous commit. The main focus of our Beta release was getting essential mechanics into play and taking feedback from the previous evaluation. While there is more to do to
guide the player, we implemented player guidance in the form of colored stones attached to doors and levers. This made the game feel a bit more navigable, and opened the door for our current work and plans: to add a map, available at checkpoints,
and add more prompts for the user. We've all done the best we can, given that everyone has a real life outside of this project, and it's coming along rather smoothly. There weren't really any tools that were unhelpful or a hinderance, as we've kept it
all rather simple, and stuck with the same tools as we have been using. Our final project is set to come out on schedule.

# Module Six Project Log - Team Reflection
Members Present: Matthew C, Carlos P, Ruben G, Jon B
## The Final Release
Overall, the final evolution of our game also came out rather smoothly. Our communication and workflow was good, and we all completed our assigned tasks. Once again there were, of course, a few hiccups. One or two corrupted files (luckily resolved before impact this time),
a couple of commits done at the same time leading to conflicts...unfortunately stuff like this happens, but we as a team handled it with patience and grace, resolving the issues efficiently.\
Previous evaluations were once again key in this development stage; we, of course, intended to add sounds and textures, but it certainly was the right next step. We also did change the interact button to 'E' because, we agree, that just makes sense.
Regarding tools, we, once again, did not greatly expand our arsenal. We used the Fab library for our assets (textures, models, and sounds). There were no tools used that did not earn their place.
