# BRICK building ventilation evaluation 
BRICK APP development
Compare air supply flow sensor measurements against their respective setpoints. The app can retrieve sensors where their measurements are above or below a setpoint, in between both the minimum and maximum setpoint values of the setpoint, or measurement exceeds either the minimum or maximum setpoint values.

The default set up is for evaluating the oversupplied air flow in BRICK buildings.

The app produces a CSV file called <sensor>_measure_vs_setpoint_<type of analysis>.csv when run where '' states the sensor type and '' states the type of analysis performed. Each row contains the following information:

site name
equipment name
number of hours that sensor measurement meets the selected criteria
start date and time that sensor measurement meets the selected criteria
end date and time that sensor measurement meets the selected criteria
measured value
setpoint value
Difference between the measured and setpoint values, i.e. measured - setpoint
