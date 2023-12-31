
<h1>Adaptive Traffic Simulation</h1>
<h2>Aim:</h2>
<p>
  The project's aim is to facilitate speedy and smooth flow of traffic at intersections while giving priority to emergency vehicles using IoT and ML. 
</p>

<img width="1396" alt="image" src="https://github.com/Aksaykanthan/Traffic_Simulation/assets/86051039/a12b8ef4-0ec1-4b45-bae1-3c6984fc84e1">

<h2>Methodology:</h2>
<p>
  We’ll be taking a smart approach to this problem by incorporating IoT based ideas and a machine learning model at the cross-sections. 
  By using the preinstalled cameras, we can use the yolo algorithm to find the number of vehicles and classify them into groups based on their respective speeds in traffic. 
  Using this data we can calculate the vehicular density of that lane and calculate the minimum time the vehicles in this lane require to leave that cross-section. 
  We would then add this calculated time with another minute to act as a cushion time and feed it to the system. The system will show green lights to the respective lanes with the respective times. 
</p>
<p>
  We can feed this cycle and data to a machine learning algorithm to understand the daily movement of traffic at cross-sections and use it as a feedback control. 
  We can also use this machine learning model to provide better results in the near future. In case a camera stops working the system will use the previously recorded data to provide respective green time to that signal. 
</p>
<p>
  In case a where emergency vehicles such as an ambulance appear, we can recognize them using their sirens from the cameras and alert the system. 
  To react to this, the system suspends the current green signal, flashes yellow signal to every lane as a case of emergency, while providing green signal only to the lane with an ambulance. 
  This would continue until the ambulance leaves the field of vision of the camera, i.e., has crossed the signal. Once the ambulance crosses the signals, the previous green signal continues. 
</p>

<h2>TODO:</h2>
<ol>
  <li>1. Implement a Reinforcement Learning to calculate the Green time</li>
  <li>2. Implement a Emergency case handler - ie. ambulance,etc </li>
  <li>3. Implement a Camera(Sensor) to automatically classify the vehicles</li>
</ol>
<br>
<p>
  Note:
  This project is under development
</p>
