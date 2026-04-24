# Instructions

1. Install the the following integrations:
- https://github.com/tmjo/charger-card
- https://github.com/Louisbertelsmann/Sungrow-Wallbox-Modbus-HomeAssistant
2. Replace your modbus_sungrow.yaml with the following:
- https://github.com/SunnyCrockett/Sungrow-SHx-Inverter-Modbus-Home-Assistant/blob/main/modbus_sungrow.yaml
3. Copy sungrow_wb_bl.png to folder www

4. Create a new dashboard, e.g. called "Charger":
- Home Assistant --> Settings --> Dashboards --> "Add Dashboard" 
-- Title: Charger
-- click "Create"

--> A new dashboard with the Name "Charger" was created

Open Dashboard and paste the content of the provided dashboard.yaml file
- Open the newly created dashboard "Charger" (left side of HA)
- Click on the "three dots" on the top right corner and select "Edit Dashboard"
- Move the slider and start with an empty dashboard
- Click "Take Control"
- Click a second time on the "three dots" on the top right corner. Now select "Raw configuration editor"
- Copy and paste the content of dashboard.yaml. Ensure that the spacing keeps intact!
- Save and reload page (press F5)

# Screenshots

![image](https://github.com/user-attachments/assets/81ec49d0-e2d5-4424-8f4b-f2e64791cc75)

![image](https://github.com/SunnyCrockett/Sungrow-SHx-Inverter-Modbus-Home-Assistant/assets/153714968/e9dc2012-ad9d-405d-8647-6f1e94e977f3)

by [SunnyCrockett](https://github.com/SunnyCrockett)
