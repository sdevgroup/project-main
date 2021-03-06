## csci3308-project
Software Development and Tools - Spring 2016 Term Project

##### Who:
- Christine Samson ([casamson](https://github.com/casamson))
- Nolan Cretney ([nokynokes](https://github.com/nokynokes))
- Evan Su ([hexacyanide](https://github.com/hexacyanide))
- Michael Xiao ([MDXiao](https://github.com/MDXiao))
- David Kleckner ([D-Kleck](https://github.com/D-Kleck))

----

##### Title:
Hunger Games: May the Odds Be Ever in Your Favor

----

##### Vision Statement:
In order to provide a source of entertainment that is available to individuals
seeking to participate in larger collaborative gaming environments, Hunger
Games: May the Odds Be Ever in Your Favor is a game with a multiplayer feature.
It's a free for all, last man standing, Hunger Games style elimination game
where players play to survive in the Hunger Games. They can use any weapons and
gadgets at their disposal and the last player alive wins. May the odds be ever
in your favor!

----

##### Automated Tests:
For our game instance server, we used [Mocha](https://mochajs.org/), a
JavaScript testing framework, to run our unit tests. The tests can be run by
cloning the
[instance-server](https://github.com/sdevgroup/instance-server/tree/master)
repository, and then running Mocha from the root directory.

    $ git clone git@github.com:sdevgroup/instance-server.git
    $ cd instance-server
    $ sudo npm install -g mocha
    $ mocha

**Output:**


![alt text](http://i.imgur.com/rswbHXU.png)

----

##### User Acceptance Tests:
---------------------------------------------------------
|            |      |
|------------|------|
| **User Case ID:** | UC-01 |
| **User Case Name:**  | Login Screen
| **Description:** | When program starts, user is shown a login screen, and requires the user to input a username to play.
| **Users:** | Anyone 
| **Pre-conditions:** | User's player can't move until username is given, username can't be blank.
| **Post-conditions:** | After the user gives a proper username, login disapears.
| **Frequency of Use:** | Whenever the game starts
| **Flow of Events:** | **Actor Action:** 
|                     | 1. Turn on game 
|                     | 2. Attempt to login without putting in username
|                     | 3. Enter Username and click login
|                     | **System Response:** 
|                     | 1. Login Screen comes up
|                     | 2. System doesn't recognize username as valid and doesn't login
|                     | 3. Login Screen disapears and player can move
| **Test Pass?:** | Pass
| **Notes and Issues:** | Possibly put a message up if user tries to enter without a username

---------------------------------------------------------
|            |      |
|------------|------|
|**User Case ID:** | UC-02 |
| **User Case Name:**  | Character Movement
| **Description:** | After user logs in, use the arrow keys to move in all 4 directions (asdw)
| **Users:** | Anyone 
| **Pre-conditions:** | User has logged in
| **Post-conditions:** | Move the direction of the of the key used
| **Frequency of Use:** | Whenever the game starts
| **Flow of Events:** | **Actor Action:** 
|                     | 1. Hold the 'W' key, then let go.
|                     | 2. Hold the 'A' key, then let go.
|                     | 3. Hold the 'D' key, then let go.
|                     | 4. Hold the 'S' key, then let go.
|                     | **System Response:** 
|                     | 1. Player moves North.
|                     | 2. Player moves West.
|                     | 3. Player moves East.
|                     | 4. Player moves South.
| **Test Pass?:** | Pass
| **Notes and Issues:** | Possibly alter code so that character moves depending on the direction he is facing rather than by direction
-----------------------------------------------------------
|            |      |
|------------|------|
|**User Case ID:** | UC-03 |
| **User Case Name:**  | Invisible Bounded Walls
| **Description:** | If a player attempts to escape the edges of the map, the map has invisible barriers to prevent them from escaping.
| **Users:** | Players/Anyone 
| **Pre-conditions:** | Player attempts to leave the avaliable game map.
| **Post-conditions:** | The map prevents them from leaping off the edge.
| **Frequency of Use:** | During game, whenever player tries to walk off edge..
| **Flow of Events:** | **Actor Action:** 
|                     | 1. Player starts walking in specified direction.
|                     | 2. Player reaches end of map, and tries to continue walking.
|                     | 3. Repeat Steps 1 and 2 for all four directions.
|                     | **System Response:** 
|                     | 1. Stops the player from running off the edges of the map.
|                     | 2. Stops the player from running off the edges of the map for each direction.
| **Test Pass?:** | Pass
| **Notes and Issues:** | Currently only implemented on forestmap, this feature will be added on future maps.


----------------------------------------------------------
