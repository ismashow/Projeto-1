Smartwatch Project – Stopwatch with Calorie Calculator

This project implements a simple smartwatch interface that allows the user to choose between three types of exercises: Swimming, Running and Lifting. The user can control the training time through a stopwatch and view the estimated amount of calories burned for each exercise in real time. The calorie calculation is customized for each type of activity, based on the accumulated time on the stopwatch.

Functions:

• Selection between three different exercises.

• Stopwatch with minutes, seconds and hundredths of a second.

• Dynamic and real-time calculation of calories burned, with specific rates for each exercise.

• Separate storage of the time for each exercise.

• Buttons to start, pause, reset the current exercise and return to the selection screen.

Technologies Used:

The project was developed using HTML5 for the page structure, CSS3 for the visual design and JavaScript to implement the stopwatch logic, exercise control and calorie calculation.

Calorie Calculation:

Calories are calculated based on specific rates for each exercise, considering the time in seconds. The rates used are:

• Swimming: 0.195 kcal per second.

• Running: 0.167 kcal per second.

• Lifting: 0.111 kcal per second.

This means that, for the same amount of time spent exercising, Swimming burns more calories, followed by Running and then Lifting.

Project Structure:

• index.html — HTML structure of the interface.

• style-aula.css — CSS styles for formatting and layout.

• scripts.js — JavaScript code for controlling the timer, selecting exercises and calculating calories.

Possible Future Improvements:

Among the improvements that can be implemented are:

• Data persistence using localStorage to keep times saved after closing the browser.

• Graphical visualization of user progress and performance.

• Customization of calorie rates according to personal data, such as weight and age.

• Improved responsiveness for devices other than smartwatches.

How to Use:

1. Open the index.html file in a modern browser.

2. Select one of the available exercises to start the timer.

3. Use the buttons to start, pause, reset the current exercise or return to the selection.

4. Watch the time and calories burned update in real time.

5. Each exercise maintains its individual time until manually reset.
