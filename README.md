<h1>Photogate</h1>

<p>Current PCB Revision: 1.0</p>
<p>PCB Part Number: L0004</p>

<p>The photogate board functions as an optical sensor for calibrating the absolute position of stepper motors upon controller startup (L0005). The photogate is mounted on the stepper motor adjacent to the motor shaft, which is coupled to the stem of a ball-valve used as the main propellant valve in SDR's liquid engine. The photogate uses an infrared LED to produce an optical signal on the infrared-sensitive phototransistor surface. The board has a characteristic U-shape that allows a small standoff strut on the motor coupler to block the optical path of the sensor when the valve reaches the closed position. </p>

<p><b>Working Directory Structure:</b></p>

<p>
   doc: documentation
   
   src: source design files, e.g. schematic and PCB layout files

   lib: libraries for schematic symbols and footprints

   production: files needed for pcb fabrication, e.g. gerbers, profile, drill file

   sim: simulation models/files 

   cad: 3d models
  
   img: images of circuit/footprints for github display 
</p>

<h2>3D Model: </h2>
<img src='img/L0004-Photogate-FRONT.jpg'>
<img src='img/L0004-Photogate-BACK.jpg'>

<h2>Schematic: </h2>

<h3>Power Supply </h3>
<img src='img/power-supply.png'>

<h3>Emitter</h3>
<img src='img/emitter.png'>

<h3>Sensor</h3>
<img src='img/sensor.png'>
