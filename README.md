# CS 350: Emerging Systems Architectures and Technologies  
## Portfolio Artifacts and Reflection

---

### Selected Artifacts

**1. Thermostat Project (`thermostat.py`)**  
This Python script demonstrates the design and implementation of a smart thermostat on a Raspberry Pi, featuring state management (OFF, HEAT, COOL), temperature sensor input, LED indicators, user input buttons, and an LCD display.

**2. Morse Code LED Project (`Milestone3.py`)**  
This Python application controls LEDs to display messages in Morse code. The project uses a state machine and button input to switch between predefined messages, offering a practical demonstration of software/hardware interaction.

---

### Reflection

**Summarize the project and what problem it was solving.**  
The Thermostat project aimed to create a simple but functional thermostat prototype using a Raspberry Pi. It reads temperature input, allows users to change setpoints, and indicates system status (heating, cooling, or off) with LEDs and an LCD.  
The Morse Code project focused on controlling LEDs to visually display different messages in Morse code, using button presses to toggle between messages. Both projects tackled the challenge of integrating hardware components with software to create interactive, real-world systems.

**What did you do particularly well?**  
I was able to break down system requirements into clear, modular code and successfully interface with hardware components (buttons, LEDs, LCD, and temperature sensors). I ensured that user input was intuitive, and provided visual feedback with LEDs and the display. The state machine approach I used made both systems easy to manage and extend.

**Where could you improve?**  
I could improve by enhancing error handling, such as managing hardware failures or debouncing button inputs more effectively. I would also benefit from providing more thorough documentation and unit tests to help others understand and further develop the code.

**What tools and/or resources are you adding to your support network?**  
I leaned on the Raspberry Pi and Python community forums, Adafruit and GPIO documentation, and Stack Overflow for troubleshooting and best practices. For future projects, I plan to incorporate more advanced debugging tools and version control practices.

**What skills from this project will be particularly transferable to other projects and/or course work?**  
These projects strengthened my Python programming, state machine design, hardware/software integration, and practical use of version control with GitHub. The hands-on experience with sensors, outputs, and user interface components is highly relevant for future embedded systems or IoT projects.

**How did you make this project maintainable, readable, and adaptable?**  
I structured both projects using clear functions and classes, included descriptive comments, and separated hardware interaction from application logic where possible. The use of state machines and modular code makes it easy to adapt the system for additional features or hardware changes in the future.




