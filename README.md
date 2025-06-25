# Interactive-Kaleidoscope


A mesmerizing and interactive digital Kaleidoscope created with p5.js. This project generates beautiful, symmetrical patterns that respond in real-time to your mouse movements, creating a unique visual experience with every interaction.



✨ Features

Symmetrical Drawing: Automatically mirrors and rotates your drawings to create complex, kaleidoscopic patterns.

Interactive Mouse Controls: The pattern is drawn based on the position and speed of your mouse.

Dynamic Line Weight: Lines become thinner or thicker based on mouse speed, and pressing the mouse button adds emphasis.

Vibrant Color Cycling: The stroke color smoothly transitions through the entire hue spectrum, creating a vibrant rainbow effect over time.

Responsive Canvas: The kaleidoscope automatically resizes to fit the full browser window.

Simple & Clean: Press any key to clear the canvas and start a new masterpiece.

🚀 How to Use?

Using the kaleidoscope is simple and intuitive: 

> Download the Kaleidoscope_xxxxxx.html (xxxxxx=version release date)

> Open Kaleidoscope_xxxxxx.html in your web browser

> Move your mouse across the canvas to begin drawing

> You can press and hold the mouse button to make the lines thicker and more dramatic

> Press any key on your keyboard to clear the screen and start fresh

📷 Screenshot


![screenshot_kali.png](https://github.com/saif-phy/Interactive-Kaledioscope/blob/112c2db0f35b031da81dc117f43f540bf3b8ca83/screenshot_kali.png)

🔧 Customization

This project is built to be easily customized. Open the script tag in the index.html file and try changing these values:

symmetry: This constant on line 35 controls the number of reflective segments. The default is 6, but try 4, 8, 12, or any other number to see how it dramatically changes the patterns!

Color Logic: Modify the stroke() function call inside draw() to experiment with different color schemes.

Drawing Tools: Instead of drawing a line(), try using other p5.js drawing functions like circle(), rect(), or even custom shapes with beginShape() and vertex().

🛠️ Built With  

p5.js - A JavaScript library for creative coding.

HTML5 & CSS3

📄 License  

This project is open source and available under the MPL-2.0 license.

👤 Author  

Developed by Saif.

If you find this tool useful, feel free contribute to the repo!
