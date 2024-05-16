# Heart_Wave
This project entailed the design and development of HeartWave, a functional device that measures, analyzes, and displays Heart Rate Variability (HRV) patterns. HeartWave utilizes an advanced heart rate monitor to provide users with real-time biofeedback based on their coherence levels.

The project includes a visual representation of how the device operates on a real person. It generates mock data that accurately reflects the coherence levels detected by the monitor.

Coherence refers to the synchronization between the heart, brain, and autonomic nervous system, offering various mental, emotional, and physical benefits. The project categorizes coherence into three levels: Low, Medium, and High.

The coherence level affects the appearance of the generated graph; a rough graph indicates a lower coherence level, while a smooth graph indicates a higher coherence level. Coherence scores range from 0 to 16.

These considerations were integral to developing the algorithms used for generating the random data to be displayed.

Members of Group
Braydon Hoard | Saajid Aliyar | Ron Stuchevsky | Maryam khalaf  |

This project was written using QT in C++. This project is easy to setup using the QTCreator IDE. It gives you a visual window and is easy to use to setup clean User Interfaces using QT C++.
Code and Files
READ THIS BEFORE BUILDING

Make sure to run the command: sudo apt-get install mesa-common-dev libgl1-mesa-dev libglu1-mesa-dev and see that the libraries are up to date or the graph feature will simply not work.

1.1 Also consider adding more memory to the VM if building freezes or is really slow

If you get a lot of build errors still then make clean and rebuild hopefully resolves.

Building the project takes around 1 minute on my VM due to the graph files size so give it some time.

Interactable Elements
Back Button
Main Menu Button
Left Button
Right Button
Up Button
Down Button
Ok Button
Power Off Button
Apply Sensor
Change Coherence Level
File Organization
Team13-HeartWave folder - contains the code for the project
Team13-HeartWave\resources - contains all the pictures used in the project
docs folder - contain UML, sequence diagrams, use case diagram as well as a pdf with use cases and traceability matrix
Readme file
Visual Representation
https://www.youtube.com/watch?v=tgrpqQ-IyIw
