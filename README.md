<h1>Phugoid Motion Dynamics</h1>

<h2>Description</h2>
Phugoid oscillations are an interesting behavior incurred by aircraft when they encounter small disturbances in pitch
angle or airspeed. When an aircraft perturbs one, or both, of these parameters it will begin to oscillate in the absence of
pilot control. It is for this reason why understanding phugoid oscillations is important, as determining the behavior of
this system has direct implications for an aircraft’s longitudinal dynamic stability. In this project we will attempt to
gather more information about the phugoid system through numerical analysis. Here are the questions we will answer:
1) What effect does varying the cruise altitude have on the phugoid system? In other words, how does changing air
density effect this aspect of aircraft stability
2) How does the phugoid system behave for different types of aircraft? In other words, How do small, medium and
large aircraft behave in phugoid motion.
We will answer these questions by varying the parameters and initial conditions defining our system to fit the aircraft of
interest. The parameters that define an aircraft in phugoid motion will be 𝑔, 𝑚, 𝜌, 𝐶𝐷 , 𝐶𝐿 , 𝑆, and 𝑇 as defined in the
nomenclature. The initial conditions will be composed of initial speed 𝑉0, initial pitch angle 𝜃0, initial altitude ℎ0, and
initial horizontal displacement 𝑥0. The following list describes how these parameters and initial conditions are varied to
evaluate the questions posed above:
• To evaluate how altitude effects phugoid motion, we will vary only the density and keep all other aircraft parameters
the same. The system will be evaluated at densities equivalent to sea level, 5 km, and 10 km. All initial conditions
will be kept the same to allow for a better comparison between results.
• To evaluate how aircraft size effects phugoid motion, parameters that are particularly dependent on aircraft size
are: mass and wing area, and they will be varied according to the aircraft chosen for analysis. The initial airspeed
of each aircraft will also vary accordingly, with all other initial conditions remaining the same.
• When testing how aircraft size effects phugoid motion, the thrust for each aircraft will be set to 0 to allow for more
consistency when comparing results.

<br />


<h2>Languages and Utilities Used</h2>

- <b>Google Collab</b> 
- <b>Python</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> 

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/7ZLEj3v.png" height="80%" width="80%" alt="Program Steps"/>
<br />
<br />
Select your spacecraft:  <br/>
<img src="https://i.imgur.com/9liQxav.png" height="80%" width="80%" alt="Program Steps"/>
<br />
<br />
Choose your orbital destination: <br/>
<img src="https://i.imgur.com/nkc7D6l.png" height="80%" width="80%" alt="Program Steps"/>
<br />
<br />
Your maximum payload is calculated:  <br/>
<img src="https://i.imgur.com/jRXyy5x.png" height="80%" width="80%" alt="Program Steps"/>
<br />
<br />
OR enter your payload:  <br/>
<img src="https://i.imgur.com/X0CPTpR.png" height="80%" width="80%" alt="Program Steps"/>
<br />
<br />
Possible orbital destinations are calculated:  <br/>
<img src="https://i.imgur.com/kSYLddY.png" height="80%" width="80%" alt="Program Steps"/>
<br />
<br />
OR display engine specifications:  <br/>
<img src="https://i.imgur.com/fOGrjUe.png" height="80%" width="80%" alt="Program Steps"/>
</p>

<h2>Tsiolkovsky Rocket Equation Explanation:</h2>
<p align="center">
The Rocket Equation: <br/>
<img src="https://i.imgur.com/ojSbSKy.png" height="50%" width="50%" alt="Rocket Equation Steps"/>
<br />
  
<br />
ISP: <br/> 
<img src="https://i.imgur.com/XVicfVF.png" height="50%" width="50%" alt="Rocket Equation Steps"/>
<br />
"ISP" (specific impulse) is the efficiency of your rocket engine. <br />
"g" is the gravitational constant. 
<br />
  
<br />
Mass Ratio: <br/>
<img src="https://i.imgur.com/70YFbvd.png" height="50%" width="50%" alt="Rocket Equation Steps"/>
<br/>
"m0/m1" is the mass ratio (initial mass/final mass). <br />
"ln" is to mathematically describe how the velocity of the rocket changes as it burns fuel (mass).
<br />

<br />
Delta V <br/>
<img src="https://i.imgur.com/5pQ81Fv.png" height="50%" width="50%" alt="Rocket Equation Steps"/>
<br />
"ΔV" is the change in velocity of the rocket. <br />
Tells us how much maneuvering a spacecraft can do such as getting into orbit.
</p>
