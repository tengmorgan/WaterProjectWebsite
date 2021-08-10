# Water Project

## 2D Plot

Problem:<br>
An air force base was found to be releasing sewage into groundwater! The spill of the sewage continues to happen without stopping! In order to protect the local residents near the air force base, we need to know where the groundwater has been contaminated and stop local residents from using groundwater. The following program can help you check which locations contain polluted water and we can stop it from being used! 

Model Application:<br> 
Look at the map, the sewage spill happens at the red dot location. Use the three built-in variables to check how the sewage spreads. Use the time variable to check the spread pattern as time passes after the start of the spill. The velocity variable represents how fast the groundwater is moving towards the right on the map. The dispersion factor is a soil property showing which direction the sewage would spread. Adjust the three variables and check how the spread pattern of the sewage changes over time! 

Questions: <br>
1) What happens to the shape of the contaminant spreading as the dispersion factor increases?<br>
2) If time and dispersion factor stay constant, what happens to the contaminant spreading as the velocity changes?<br>
3) Observe and describe the shape of the contaminant spreading as times goes on. Does the spreading pattern stop changing after a specific period of time?

Advanced Questions:<br>
1) The local city policy sets the limit of concentration at 3 kg/m^2 before the underground water can threaten the health of local residents. With a flow velocity of 2.1 meter/day, dispersion factor of 0.1, and aquifer thickness of 3 meters, would the residents live near (x=60000,y=0) be able to use underground water safely after 6 years?  <br>
2) Knowing the flow velocity is 1.1 meter/day, dispersion fraction is 0.05, and aquifer thickness is 3 meters, after how much time the concentration would reach a steady state if no other variables are considered? <br>
*Steady State refers to the status where the concentrations are not changing anymore in the area of interest.

[Click here for the 2D web application](https://twodimensiontesting.herokuapp.com/)

## 1D Plot
Problem:<br>
On a hot summer day, lab assistant Sally was given a task to disposal a bottle of chemical. Without much thinking, she pours the chemical right down the drain! It was later found that the chemical being poured is benzene and spills directly into the groundwater! In order to prevent the local residents using the contaminated water, use the following contamination model to check the spread of the benzene. 

Model Application:<br> 
The program gives you a plot which represents the chemical concentration at different distances towards east (right) from the lab. The program also gives you two ways to model what happened after Sally poured the chemicals. You may choose the type of soil that the chemicals are going into and you may adjust the how much chemicals was poured. Use the two methods in the program and check how the concentration of the chemical changes at different locations over time.

Questions: <br>
1) What is the effect on the maximum concentration when porosity increases? <br>
2) If the pollution mass, porosity, and absorption all stay constant, what happens to the concentration as time goes on?<br>
3) Don't change the pollution mass and porosity, observe and describe the changes to the curves as absorption changes?<br>

Advanced Questions:<br>
1) A spill occurred into an aquifer near UC Davis! The spill mass is known to have a mass of 800 kg, and soil test shows that the porosity of the aquifer is 0.36 and the absorption is 2.5. How far away horizontally can we expect the maximum concentration to occur after 5 days? and 20 days? <br>
2) The city policy of Davis allows 20 kg/m of concentration for this contaminant. Knowing the porosity and absorption is 0.34 and 4.35 respectively. What is the maximum spill mass allowed in the aquifer before violating the local environmental policy?

[Click here for the 1D web application](https://onedimensiontesting.herokuapp.com/)
