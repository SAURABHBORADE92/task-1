This Python program uses the tkinter library to create a graphical BMI (Body Mass Index) calculator. The application window is titled "BMI Calculator" and has a clean layout with sliders for inputting weight in kilograms and height in centimeters. As the user adjusts these sliders, the values are fetched using DoubleVar() variables. The function calculate_bmi() is triggered every time a slider is moved or the button is pressed. It retrieves the current weight and height, converts the height from centimeters to meters, and then calculates the BMI using the formula: BMI = weight / height². The result is displayed in a formatted label as "xx.xx kg/m²".

The interface also includes a styled section that displays the calculated BMI and a default health message encouraging users to discuss their result with a healthcare provider. A button labeled "Get Health Tips" allows manual triggering of the BMI calculation. The app uses modern themed widgets via ttk, giving the GUI a polished look. Exception handling ensures that any invalid input doesn't crash the program and instead shows a friendly error message. Overall, it’s a beginner-friendly example that combines GUI design, real-time data binding, and simple arithmetic logic.
You open the app – a window appears with sliders to choose your weight and height.

You move the sliders – you can adjust your weight (e.g., 70kg) and height (e.g., 170cm).

Instant Calculation – As soon as you change the values, the program:

Converts height from cm to meters.

Gives Health Tip – It gives a message explaining what the BMI means and suggests you talk to a doctor.

📦 What’s Inside the App?

Weight & Height Sliders: You can adjust them easily.

Live Value Display: It shows your current selection.

BMI Box: Shows your BMI and some helpful health tips.

Health Button: Just in case you want to recalculate.
