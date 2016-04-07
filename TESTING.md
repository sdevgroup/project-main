## csci3308-project
Software Development and Tools - Spring 2016 Term Project

##### Who:

- Christine Samson ([casamson](https://github.com/casamson))
- Nolan Cretney ([nokynokes](https://github.com/nokynokes))
- Evan Su ([hexacyanide](https://github.com/hexacyanide))
- Michael Xiao ([MDXiao](https://github.com/MDXiao))
- David Kleckner ([D-Kleck](https://github.com/D-Kleck))

##### Title:
Hunger Games: May the Odds Be Ever in Your Favor

##### Vision Statement:
In order to provide a source of entertainment that is available to individuals seeking to participate in larger collaborative gaming environments, Hunger Games: May the Odds Be Ever in Your Favor is a game with a multiplayer feature. It's a free for all, last man standing, Hunger Games style elimination game where players play to survive in the Hunger Games. They can use any weapons and gadgets at their disposal and the last player alive wins. May the odds be ever in your favor!

##### Automated Tests:
https://mochajs.org/
For intance-server, we used [mocha](https://mochajs.org/) to run our unit tests. To run the tests, make sure you are in the instance-server directory, and type "mocha" into the terminal. Make sure you have mocha installed.


Output:
![alt text](http://i.imgur.com/rswbHXU.png)

##### User Acceptance Tests:
---------------------------------------------------------
|            |      |
|------------|------|
| **Use Case ID:** | UC-01 |
| **Use Case Name:**  | Login Screen
| **Description:** | When program starts, user is shown a login screen, and requires the user to input a username to play.
| **Users:** | Anyone 
| **Pre-conditions:** | User's player can't move until username is given, username can't be blank.
| **Post-conditions:** | After the user gives a proper username, login disapears.
| **Frequency of Use:** | Whenever the game starts
| **Flow of Events:** | **Actor Action:** 
|                     | 1. turn on game 
|                     | 2. attempt to login without putting in username
|                     | 3. enter Username and click login
|                     | **System Response:** 
|                     | 1. Login Screen comes up
|                     | 2. system doesn't recognize username as valid and doesn't login
|                     | 3. Login Screen disapears and player can move
| **Test Pass?:** | Pass
| **Notes and Issues:** | Possibly put a message up if user tries to enter without a username

---------------------------------------------------------
|            |      |
|------------|------|
|**Use Case ID:** | UC-02 |
| **Use Case Name:**  | Login Screen
| **Description:** | When program starts, user is shown a login screen, and requires the user to input a username to play.
| **Users:** | Anyone 
| **Pre-conditions:** | User's player can't move until username is given, username can't be blank.
| **Post-conditions:** | After the user gives a proper username, login disapears.
| **Frequency of Use:** | Whenever the game starts
| **Flow of Events:** | **Actor Action:** 
|                     | 1. turn on game 
|                     | 2. attempt to login without putting in username
|                     | 3. enter Username and click login
|                     | **System Response:** 
|                     | 1. Login Screen comes up
|                     | 2. system doesn't recognize username as valid and doesn't login
|                     | 3. Login Screen disapears and player can move
| **Test Pass?:** | Pass
| **Notes and Issues:** | Possibly put a message up if user tries to enter without a username

-----------------------------------------------------------
|            |      |
|------------|------|
|**Use Case ID:** | UC-03 |
| **Use Case Name:**  | Login Screen
| **Description:** | When program starts, user is shown a login screen, and requires the user to input a username to play.
| **Users:** | Anyone 
| **Pre-conditions:** | User's player can't move until username is given, username can't be blank.
| **Post-conditions:** | After the user gives a proper username, login disapears.
| **Frequency of Use:** | Whenever the game starts
| **Flow of Events:** | **Actor Action:** 
|                     | 1. turn on game 
|                     | 2. attempt to login without putting in username
|                     | 3. enter Username and click login
|                     | **System Response:** 
|                     | 1. Login Screen comes up
|                     | 2. system doesn't recognize username as valid and doesn't login
|                     | 3. Login Screen disapears and player can move
| **Test Pass?:** | Pass
| **Notes and Issues:** | Possibly put a message up if user tries to enter without a username

----------------------------------------------------------
