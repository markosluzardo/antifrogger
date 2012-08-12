# AntiFrogger

A game designed for Android with [AndEngine](http://www.andengine.org/) developed within the [Android Aalto](http://androidaalto.org/) Hackatons and the freetime of the contributors.

## The Game

Side-scrolling 'racing' game centered on a car. The objective is to get as many frogs as you can, the car is moved tilting the phone. The frogs win a game session with a certain amount of missed frogs depending on the reached level.

> A new view over the original Frogger. This time you are the car.

# Changelog

## Version 0.2a

- Game concept functional
- Changed resources
- Updated sprites
- Added splash screen
- Added main menu

## Known issues
- Motion controls with wrong axis (Android 4.0.4)
- Game does not restart (Game)

## Contributor considerations
The game requires the AndEngine project and libraries to compile. Also the java compiler must be set to version 1.6 or above.

# Roadmap

The game as its current state have the following pending changes to be included towards the first *stable version* code. If you are an interested contributor please **pick one of this points** or **make a suggestion** so it can be included in the main branch.

- Make the camera follow the car instead of using a fixed camera position
- Track the number of missed frogs
- End level on either win or lose and return to menu screen
- Increase speed at each level
- Add car sprites to respond to diverse road areas
- Change frog sprites
- Add smart frogs with preentive behaviour
- Implement leaderboards

Future mayor versions will implement different game elements such as:

- Implement items/power-up system
- Implement dynamic road/game conditions

If you want to get more details over each point feel free to ask.