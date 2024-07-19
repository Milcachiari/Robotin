Good morning, afternoon or evening, distinguished jurors.

 It is a real pleasure to be here today to present our project “Robotin”, which has been developed with dedication and effort using Lego EV3 materials and programming through Lego Classroom.  This project has been a collaborative effort with my dedicated team, where we have integrated two motors into Robotin's design, including two color sensors and a servo motor.

Sensors and servo motors
To keep things simple, the sensor that detects the red and green colors will be sensor A, and the sensor that detects the track stripe will be sensor B. With this I continue with the explanation.

Robotin has two motors, which fulfills a function that is that the motors drive the back and the front of the robot forward and backward. Sensor A detects red or green colors. When Robotin detects the color red, it autonomously moves back approximately 6 centimeters. The rear motor then executes a sequence: a right rotation of 0.5 seconds followed by a rapid left rotation of 0.05 seconds. It then resumes forward motion along its trajectory. Similarly, when Robotin detects green, it moves back the same distance of 6 cm. However, the rotation sequence is different: a leftward rotation of 0.05 seconds is followed by a rightward rotation of 1.5 seconds, before moving forward again after 1 second.

Sensor B detects the blue color at the bottom, i.e., it reads the track. If Robotin detects the blue color, it makes a clockwise or counterclockwise rotation depending on the position on the track to avoid hitting the walls. The servomotor's job is to move left or right depending on what the color sensors indicate. We programmed that if the color sensor detects red, it will give a rotation of 0.08 to the right; if it detects green, it will give a rotation of 0.08 to the right. But in the bottom sensor, which detects the stripes of the track, which would be the blue color, depending on the direction (clockwise or counterclockwise), it will move to avoid collisions. Initially, we had sensor B detect the light intensity, but we had difficulty getting it to read the color, so we let it detect only the blue color.

Challenges and Solutions
We had a lot of difficulties since it was the first time using EV3 and at the same time programming, but despite the difficulties we managed to finish Robotin. Every obstacle became an opportunity for learning and improvement. For example, in the beginning, sensor calibration was a considerable challenge. We realized that the lighting of the environment significantly affected the accuracy of the color sensors, which led us to implement dynamic calibration algorithms that adjusted the sensor values in real time.

Transition from Arduino to Lego EV3
Initially conceived as a prototype using Arduino, we ran into technical challenges that led us to transition to Lego EV3 as our platform of choice. Despite being novices with Lego EV3 components, we overcame the initial complications with resilience and determination. Our journey has been marked by these obstacles, but our commitment to overcoming them remains steadfast as we strive for success in this project.                                                                        
     
Learnings and Continuous Improvement
Throughout Robotin's development, we learned valuable lessons about teamwork, problem solving, and documenting every step and every adjustment made allowed us to quickly identify problems and correct them efficiently. In addition, we learned to appreciate the importance of iterative testing; each test provided us with data that we used to refine and improve Robotin's performance.
                                                                                                                                                                                             
Project Impact and Future Applications
Robotin is not only a testament to our technical capability, but also to our ability to work as a cohesive team. We believe this project has the potential to inspire other students to explore the world of robotics and programming. In the future, we would like to expand Robotin's capabilities, incorporating more sensors and advanced artificial intelligence algorithms to improve its autonomy and efficiency.                                                                                     
                                                                                                                                                                                                                                                                    

Conclusion
In conclusion, our “Robotin” project has been an incredibly enriching experience. Through this project, we have not only gained valuable technical skills, but we have also learned the importance of teamwork, perseverance, and innovation. We are excited about future possibilities and grateful for the opportunity to present our work to you.

