## CARD BATTLER

## Team Information

**Name:** TAYLO, CLARK KENNETH | ZAMORA, SEAN MATTHEW

**Section:** 9339-AY225

**Course:** BSCSIT 1203 Programming 2

**School:** University of Perpetual Help System DALTA – Molino Campus

---
## Final Project Details

**Title: Card Battler**

A high-stakes, strategic card game where you face off against a computer AI to predict the flow of the deck. Built for the Trio Bisaklat project.

## Game Description
*Card Battler* is a web-based "High or Low" competitive game. Unlike traditional card games, this features a dynamic Player vs. CPU environment. Players start with a "Primordial Card" and must predict if the next card drawn will be higher or lower in value. 

The game logic uses a 52-card deck divided into four sets of 13, where values are calculated regardless of the suit. It features a multi-stage reveal system to build tension, persistent score history, and an adaptive UI that focuses on the action as the battle progresses.

## Setup Instructions
To run the game locally:
1. *Clone the repository:*
   ```bash
   git clone [https://github.com/](https://github.com/)[your-username]/card-battler.git

2. *Prepare the Assets:*
    Create a folder named images/cards/.
    Place your card images (named 1.jpg to 52.jpg) inside that folder.
    Add a back.jpg (card back design) in the same directory.

3. *Run the Game:*
    Open *index.html* in any modern web browser (Chrome, Firefox, or Edge). No local server is required.

## List of Controls
*Enter Arena*: Click the main button on the landing page to start.

*Player Setup*: Input your nickname to personalize the HUD.

*Card Selection*: Choose 1 of 4 mystery cards to set your starting value.

*Higher (↑) / Lower (↓)*: Click these buttons to predict the next card's value.

*Peek Board*: Temporarily hides the overlay for 5 seconds to let you analyze previous draws.

*Score History*: Check the "Score History" button on the home screen to see the last 10 battle results.

## Game Mechanics & Scoring
Value Logic: The game treats cards 1-52 as four sets of 1-13.

CPU Opponent: A randomized AI (Viper, Glitch, etc.) makes its own predictions simultaneously.

## Scoring:
Correct Prediction: +100 Points

Wrong Prediction: -50 Points

Expansion: After the first round, the UI sidebars fade away, and the card grid expands for a more immersive view.

    ---