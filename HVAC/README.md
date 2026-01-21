This is how I control our HVAC with two Ecobees. Our older home is fairly simple with two zones, upstairs and downstairs.  I treat each floor a little differently since the bedrooms only exist upstairs, so the nighttime mode is a little different. The sensors I want to use are done in Helper Groups to simplify the automations are prevent many sensors in them.

The automations and helpers do the following:

- 3 modes, Home, Away, Sleep autodetecting those based on a combination of Geofencing with our phones and various motion sensors in the house.
- Summer/Winter modes.
- HVAC automatically shuts off if doors/windows left open for an extended period of time, and will resume when they are closed.
- Detecting a manual temp change from the unit or card in HA starts a 2 hour countdown where the automation is disabled in favor of your setting.
- +/- 3 degree temp changes in settings based on outside temp - cooler in the summer, warmer in the winter.

To-do: Excessive temp and/or Co2 detected in furnace room should turn off the HVAC.
