# Instructions

1. Install the the following integrations:
 https://github.com/tmjo/charger-card
 https://github.com/Louisbertelsmann/Sungrow-Wallbox-Modbus-HomeAssistant

2. Copy sungrow_wb_bl.png to folder www

3. Create a new dashboard, e.g. called "Charger":
- Home Assistant --> Settings --> Dashboards --> "Add Dashboard" 
-- Title: Charger
-- click "Create"

--> A new dashboard with the Name "Charger" was created

3.1. Open Dashboard and paste the content of the provided dashboard.yaml file
- Open the newly creadet dashboard "Charger" (left side of HA)
- Click on the "three dots" on the top right corner and select "Edit Dashboard"
- Move the slider and start with an empty dashboard
- Click "Take Control"
- Click a second time on the "three dots" on the top right corner. Now select "Raw configuration editor"
- Copy and paste the content of dashboard.yaml. Ensure that the spacing keeps intact!
- Save and reload page (press F5)
