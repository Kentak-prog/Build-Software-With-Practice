App Name: 3D MPC Drone Tuner
Description: This app is a simulator for a drone using a mpc scheme to control it. The user can click to adjust target position as well as adjust its weights to influence trajectory.
The user can push a button to create disturbances and adjust altitude. Two graphs show the altitude version time and the control effort of the drone. There is a legend with specific 
statistics for the users general knowledge. 
App Deployment: https://enchanting-marshmallow-ee1930.netlify.app/
Technology components: Html was the language of choice and Copilot was the AI tool that help generate my idea into code. The data is also stored using Google's Firebase.
Setup:
 - No setup is needed just access the link to the live hosting and begin saving and adjusting gains to your desire.
 - The rest is handled by the database.
Demo Video Link: https://youtu.be/AY6qNvDcVSo
App Functionality: The app's main purpose is to simulate a drone flying towards a target using model predictive control. Weights can be adjusted (position, velocity, acceleration, prediction, etc).
These calculations are plotted in real time for the user to see. The main purpose is to allow my team members working on the mpc to tune gains in a separate environment workspace.
