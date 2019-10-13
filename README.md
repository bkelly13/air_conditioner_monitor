# air_conditioner_monitor
Monitor multiple parameters of air conditioning system
This project will monitor multiple parameters of a residential air conditioning unit.
The sensors for the compressor unit are:
1. Pressure of high pressure Freon out of the unit
2. Pressure of low pressure Freon into the unit
3. Temperatore of high pressure line
4. Temperature of low pressure line
5. Temperature of compressor output before condensing coils
6. Temperature of ambient air
7. Temperature of air exiting the unit
8. Voltage supplied to the unit
9. Compressor current
10. Fan current

Sensors for the air handler (evaporator) unit
1. Pressure of high pressure line into the handler
2. Pressure of low pressure line out of the handler
3. Temperature of high pressure line
4. Temperature of low pressure line
5. Temperature of air in from house
7. Temperator is air out to house
8. Maybe air pressure sensor in inlet side
9. Maybe air pressure sensor in outlet side

The two sensors are widely separated and will have Ethernet connection.  A Cat 5 cable is in the attic from the compressor unit into the garage near the air hander.  There is a remote wireless device already in place that communitates with a monitor for the solar panels.  These two will connect to the Ethernet switch that connects to the wireless remote point.

Therefore, The code starter is an ethernet example found with a search.  It did a couple of analog reads and provided the data to a client.  That code provided the analog sensors by just entering the IP address into Chrome or MS Edge and the values were displayed.



