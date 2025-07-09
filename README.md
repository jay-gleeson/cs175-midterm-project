<div align="center">
  <img alt="GitHub License" src="https://img.shields.io/github/license/jay-gleeson/cs175-midterm-project">
  <img src="https://img.shields.io/badge/C++-%2300599C.svg?logo=c%2B%2B&amp;logoColor=white" alt="C++">
</div>

# CS175 Midterm Project Fall 2024

**EUCLID**, a game of interdimensional adventure! 🌌🧳

## **Game Overview** 🎮
*Euclid* is an interactive text-based adventure game where you, the player, take on the role of a lone adventurer with a hazy memory. A mysterious voice, Isaac, speaks to you from above, guiding you through your journey. However, Isaac is an unreliable narrator, and you’ll need to make your own decisions to navigate the challenges that lie ahead.

As you venture through this strange world, you will face multiple choices that could alter your fate. Will you take the mysterious amulet? 💎 Will you cross the great chasm? 🌉 Will you solve the riddle posed by the knight guarding the castle? 🏰 Every choice you make will have a consequence, and only the right decisions will allow you to progress.

## **Gameplay Features** 🕹️
- **Choices that Matter**: Your decisions shape the outcome of the game. Choose wisely! ⚖️
- **Isaac, the Unreliable Narrator**: A voice from above that gives you guidance — or does it? 👀
- **The Amulet**: Will you take the amulet to protect yourself from the beast lurking beneath the bridge? 🐉
- **Riddle Solving**: Solve a riddle posed by an armed knight to proceed into the castle. 🏰🔑
- **Merchant Stand**: A mysterious merchant with a spinning wheel of fate. The item you receive determines your future. 🎲🎁

## **How to Play** 🧭
1. **Start the Game**: Upon starting, you will be prompted by Isaac, the narrator, to make decisions that will shape your journey. 🌟
2. **Make Key Choices**: As you progress, you’ll need to choose between different options, like taking the amulet or crossing the chasm. 🤔
3. **Solve Riddles**: You'll encounter a knight guarding the castle. Solve his riddle to gain access. 🧩
4. **Interact with the Merchant**: At the end of your journey, you’ll have a chance to interact with a mysterious merchant to shape your future. 🛍️
5. **Multiple Outcomes**: Your decisions may lead to different outcomes, so play again to explore new paths! 🔄

## **Installation Instructions** ⚙️
1. Clone the repo:
   ```bash
   git clone https://github.com/jay-gleeson/cs175-midterm-project.git
   ```
2. Open directory:
   ```bash
   cd cs175-midterm-project
   ```
3. Compile cpp:

   A. Windows:
      ```bash
      g++ MyMidtermProject.cpp -o euclid.exe
      euclid.exe
      ```
   B. MacOS / Linux:
      ```bash
      g++ MyMidtermProject.cpp -o euclid
      ./euclid
      ```
## Challenges ⚠️
Narrative Cohesion 🧵: Maintaining a consistent tone and logical flow between branches was tricky with multiple story paths.

State Tracking 🔄: Tracking the player’s key decisions (amulet, riddle, etc.) across different scenes required careful use of variables and conditionals.

Dynamic Ending Logic 🧠: Ensuring that the ending properly reflected the player's choices involved juggling several layers of branching logic.

## Future Improvements 🚀
Save/Load System 💾: Implementing the ability to save progress and resume later for a smoother player experience.

Expanded Narrative Paths 🧭: Introduce more choices and subplots to deepen replayability and immersion.

Fix Comments for Readability 💬: Reduce comment length for in-line and block comments for better reproductability and readability.

---

Enjoy your adventure in *Euclid* 🛤️ and may your choices lead you to a good fate! 🍀✨
