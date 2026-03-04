🖋️ Air Pen: AI-Powered Virtual Drawing
A cinematic, real-time air-drawing application that uses Computer Vision to turn your hand gestures into golden ink. Using MediaPipe, this project allows you to write in the air with high precision and smooth, glow-effect strokes.

🌟 Features
Real-Time Hand Tracking: Pins the drawing point perfectly to your index finger.

Smoothing Engine: Built-in math to eliminate hand jitters, making the "ink" flow naturally like a real calligraphy pen.

Cinematic Aesthetics: Dark-themed interface with a golden glow effect, designed to look elegant on screen.

Precision Control: Uses keyboard modifiers to ensure you only draw exactly when you want to.

🚀 How to Use
Allow Camera Access: Open the HTML file in your browser and grant permission to use your webcam.

The "Shift" Trick: Hold the SHIFT key on your keyboard to start drawing. This is the secret to keeping your work clean—it allows you to move your hand to a new spot without leaving "drag marks" on the canvas.

Moving the Pen: Simply let go of the SHIFT key to move your hand to the next letter or shape.

Clear the Screen: If you make a mistake or want to start over, hit the SPACEBAR to wipe the canvas clean.

Experiment: Feel free to mess around with the colors in the code or adjust the smoothing math to fit your drawing style!

🎨 Customization
You can easily modify the following in the code:

Colors: Change the ctx.strokeStyle to any color you like.

Line Thickness: Adjust ctx.lineWidth for a bolder or finer look.

Smoothing: Change the multiplier (currently 0.45) to make the pen more or less "weighty."
