## Pong Game

## How to Clone This GitHub Project

This README provides instructions on how to clone this GitHub project to your local machine.

**Prerequisites:**

* Git installed on your local machine
* A command prompt or terminal

**Cloning the Project:**

There are two main methods for cloning the project:

**1. Using HTTPS URL:**

1. **Open the project page on GitHub.**
2. Click the **Code** button and copy the **HTTPS URL**.
3. Open a **command prompt** or **terminal** on your local machine.
4. Navigate to the directory where you want to clone the project.
5. Run the following command, replacing `<URL>` with the copied HTTPS URL:

```
git clone <https://github.com/developer-in-world/PingPong.git>
```

This command will download the project files to your local machine and create a new directory for the project.

**2. Using SSH URL:**

1. **Open the project page on GitHub.**
2. Click the **Code** button and choose the **SSH** option.
3. Copy the displayed **SSH URL**.
4. Open a **command prompt** or **terminal** on your local machine.
5. Navigate to the directory where you want to clone the project.
6. Run the following command, replacing `<URL>` with the copied SSH URL:

```
git clone <git@github.com:developer-in-world/PingPong.git>
```

This command will download the project files to your local machine and create a new directory for the project.

**Additional Notes:**

* If the project is private, you will need to be logged in to your GitHub account before you can clone it.
* You can specify a specific branch or commit to download using the `-b` or `-c` flags with the `git clone` command.
* For more information on using Git, you can refer to the official Git documentation: [https://git-scm.com/](https://git-scm.com/)

**After Cloning:**

Once you have cloned the project, you can access and use it like any other project on your local machine. You can use your preferred code editor or IDE to open and modify the files, and you can run any scripts or programs that are included in the project.

**Contributing to the Project:**

If you would like to contribute to this project, you can fork the repository and create a pull request. Please refer to the project's contribution guidelines for more information.

**Happy coding!**

## Ping Pong  game using Pygame

This is a simple implementation of the classic Pong game in Python using the Pygame library.

### Features

* Two paddles controlled by keyboard arrows
* Ball that bounces off paddles and walls
* Scorekeeping is not implemented
* Ball speed increases on collision with a "gadget"

### Instructions

1. Download the code and save it as a `.py` file.
2. Install Pygame library using `pip install pygame`.
3. Run the program using `python <filename>.py`.
4. Use arrow keys `up`, `down`, `w`, and `s` to control the paddles.
5. Press `right` and `d` to activate the "gadgets" which increase ball speed.

### Code Breakdown

The code is divided into several sections:

* **Imports:** Imports necessary libraries for game development (pygame).
* **Initialization:** Initializes pygame, sets screen size, caption, and colors.
* **Ball definition:** Defines initial position, radius, and velocity of the ball.
* **Paddle definition:** Defines initial position, width, height, and velocity of paddles.
* **Gadget definition:** Variables to track gadget activation and limit usage.
* **Game loop:**
    * Fills the screen with black color.
    * Handles user input for paddle movement and gadget activation.
    * Updates ball's movement based on collisions.
    * Updates paddle movement based on user input.
    * Applies gadget effects on ball speed when activated.
    * Draws ball, paddles, and gadgets on the screen.
    * Updates the display.

### Contributions

Feel free to contribute to this project by:

* Adding scorekeeping.
* Implementing sound effects.
* Adding difficulty levels.
* Creating a menu system.
* Customizing the game graphics.

