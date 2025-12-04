# Swing_Simulator
Developed an advanced Graphical User Interface (GUI) application in JavaFX to simulate realistic swinging motion and control animation dynamics.
# JavaFX Interactive Swing Simulator

**Note:** Please remember to replace the placeholder links/paths for your images (background and cat) with valid links or file paths within your repository after you upload the files.

## Project Overview

This project is an advanced Graphical User Interface (GUI) application developed using **JavaFX**. Its primary goal is to simulate realistic and dynamic swinging motion while giving the user full control over the animation's properties. It serves as a practical demonstration of advanced animation techniques and interaction handling within the Java ecosystem.

## Key Technical Features

This project highlights several key skills in JavaFX application development:

| Feature | Technical Implementation |
| :--- | :--- |
| **Arc Motion Simulation** | Uses the **`PathTransition`** class to precisely animate the swing chair along an **`Arc`** path, mimicking a natural, pendulum-like movement. |
| **Dynamic Speed Control** | Implements event handlers for buttons (`Play`, `Pause`, `Increase/Decrease Speed`) to provide real-time control over the animation's lifecycle and rate using **`setRate()`**. |
| **Property Binding** | Utilizes **`layoutXProperty().bind()`** to link the position of the passenger object (the cat image) to the moving swing chair's translation properties, ensuring they move cohesively. |
| **Multi-Layered Animations** | Integrates an additional visual effect using **`FadeTransition`** (for the traffic light simulation) to demonstrate the ability to manage multiple concurrent animations. |
| **Responsive Layout** | Employs property binding to size the background image (`ImageView`) dynamically to the scene's width and height, ensuring a clean display regardless of window size. |

## Requirements and Setup

To run this project locally, you will need:

1.  **Java Development Kit (JDK):** Version 8 or newer (with JavaFX support, or using JavaFX SDK/Modules).
2.  **Integrated Development Environment (IDE):** Such as IntelliJ IDEA or Eclipse.

### Execution Steps

1.  **Clone the Repository:**
https://github.com/maryamabuloha/Swing_Simulator

3.  **Import Project:** Import the directory into your IDE as a standard Java or JavaFX project.
4.  **Verify Media Files:** Ensure that your image files (e.g., `cat.png`) are correctly placed and their paths in the code (`new Image("...")`) are accurate.
5.  **Run:** Execute the `Trial.java` class.

## Visual Preview

[INSERT A SCREENSHOT OR GIF OF THE SWING ANIMATION HERE]

## License

This project is currently published without an explicit open-source license. The code is publicly visible but is subject to **All Rights Reserved** copyright restrictions.
