# Halloween Hideout Portfolio

Halloween Hideout is a 2D iOS platformer centered around surviving Halloween night, from the hours of 7 pm to 7 am. The game will consist of levels that will take place at different times in the game and get progressively harder. Throughout the player’s journey they will collect candy pieces with value ranging from one (1) to fifteen (15). These candy pieces will be used in the in-game store to buy costumes that will randomly appear throughout the levels.  The player will be able to run, jump, and attack to clear the levels and complete the game.

The purpose of this application is to develop a 2D iOS platformer that will allow a player to go through multiple levels varying in difficulty in order to survive the night. The goal is to develop a game that is easy to use, distracts some users from stressful events in their lives, and provides mindless entertainment to others.
Halloween Hideout is a passion project for the developer who wanted to find to mix love of video games with wanting to create an application that will help others. This can be as simple as taking someone’s mind off a bad day for a few hours. Halloween Hideout aims to be the game people play when they need a break.

[Project Proposal](documents/Project-Proposal.docx)

## Functional and Non-Functional Requirements
### Functional Requirements
* User can collect candy
* Candy can be used to purchase costumes in the shop
* Costumes appear in levels after purchase
* Candy has a value of 5, 10, and 15 respectively
* Enemies will be randomly placed throughout the level
* Player can pick between 3 characters to play as
### Non-Functional Requirements
* Resize the screen depending on the device. Supports iPhones 6 - 12

[Project Requirments](documents/project-requirements.docx)

[Functional Requirements](documents/functional-requirements.xls)

## Technologies
The following tools, languages, frameworks, and libraries were learned for this project. These technologies were chosen because they are all available in the Swift language and the XCode IDE. The SpriteKit and the GameplayKit is also optimized for mobile game development on iOS.

The application is not currently on the AppStore. In the event the application will get deployed to the AppStore the OSLog library will be implemented into the application to assist with debugging if need be.

### Tools
* XCode v 12.1
### Languages
* Swift v 5.3
### Frameworks
* SwiftUI v 5.3
### Libraries
* SpriteKit v 5.3
* CoreAudio v 5.3
* CoreAudioKit v 5.3
* CoreAnimation v 5.3
* NSUserDefaults v 5.3
* GameplayKit v 5.3

## Technical Approach
The CoreAnimation library will be used to animate the player, enemies, and other parts of the application that will need to be animated. The CoreAudio and CoreAudioKit libraries will be used to add background music, sound effects, and allow the user to change the volume of the audio. SwiftUI will be used to create the storyboards. UserDefaults will be used to manage the save data. The GameplayKit and SpriteKit will be used to manage the sprites and game logic. OSLog will be used to log application events for debugging. These libraries and frameworks were chosen to make the development process easier and utilize the tools given within the language.

[Project Design](documents/project-design.docx)

The following flowchart showcases the overall flow of the application.
<img src="/diagrams/Hideout Flowchart.png" alt="flowchart" width="1000" height="1000" />

The following sequence diagram showcases the process of buying a costume from the store
<img src="/diagrams/Hideout Sequence Diagram.png" alt="sequence diagram" width="750" height="750" />

The following images are pictures from the application.
### Main Menu
<img src="/application-photos/main-menu.PNG" alt="main-menu" width="1000" height="750" />

### Settings
<img src="/application-photos/settings.PNG" alt="settings" width="1000" height="750" />

### Costume Shop
<img src="/application-photos/costume-shop.PNG" alt="costume-shop" width="1000" height="750" />

### Game Over
<img src="/application-photos/game-over.PNG" alt="game-over" width="1000" height="750" />

## Risks and Challenges

The risks that I had during the application came from not knowing the Swift language, I had not done game development before, and I had not done mobile development before. To overcome these risks, I spent a lot of time going tutorials, especially on YouTube, to learn the Swift language and gameplay design. I also talked to an Indie game developer at the beginning of my project planning to gain insight on game theory, game design, where to get assets from, and tips on how to complete the application. I started working on the tutorials as often as I could to make sure I could avoid my risks turning into issues.

###### There are no outstanding issues. There are some minor bugs but they do not impact the functionality of the application.
