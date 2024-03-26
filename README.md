# StopClock



Introduction: We will build the GUI(graphical user interface) Stopwatch application using python with Tkinter. Tkinter is a python GUI package. Tkinter is the fast and easiest way to create GUI applications. We will create start, pause, stop and quit buttons to control our application.

Project Requirements: For writing code, there must be a text editor on your pc (any text editor). There must be a python installed in your system That’s it you’re ready to go.

Let’s Start:

Steps:

Create a new file with any name you like. Open that file with a text editor of your choice. We are using vs code. Now create a folder with stopwatch.py (you can use any name you like just add .py at the end) Now programming and programming logic begins (Final Code)




Explanation:

First, we import all the important libraries and modules Then we created the main window using Tkinter and we use geometry to size the window then we gave it a title. To create a label for the time we use tk.label there we put our time in the font type and font size then we use the pack to pack it into the window. Then we created the start, pause, reset and quit buttons. To create the button we use tk.button then we put in the text the height the width the font type and font size. To make our button work we created the start, pause, reset and quit functions. Then there for command, we assign the function that will be called when we click the button and for each button, we use a pack to pack into the window And to run the app we use root.mainloop().
