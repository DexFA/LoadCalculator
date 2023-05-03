Certainly! Here is the updated README.md content without the open-source reference and the License section:

# Solar System Sizing Calculator

A web application designed to calculate and recommend the optimal solar energy system configuration based on user input for electrical loads, battery storage, inverter capacity, solar panels, and backup time. This project is implemented using HTML, CSS, and JavaScript.

## Features

- User input for electrical loads (with the ability to add and remove rows for different appliances)
- Automatic calculation of total wattage and watt-hours
- Calculate total power to be generated based on level of tolerance, battery bank power, and total watt-hours
- Recommendations for battery bank power, inverter capacity, number of solar panels, and backup time
- Support for Lead Acid and Lithium-Ion batteries

## How to Use

1. Clone this repository to your local machine.
2. Open the `index.html` file in your browser.
3. Enter the details for each electrical load (appliance, quantity, wattage, and runtime) and click the "Add" button to add more rows as needed.
4. Adjust the values for tolerance, peak sunshine, desired backup time, battery voltage, and other parameters as needed.
5. Click the "Calculate" button to view the results, which include total wattage, total watt-hours, battery bank power, inverter capacity, number of solar panels, and backup time.
6. You can also view recommendations for Lead Acid and Lithium-Ion batteries.

## Functions

This application uses the following JavaScript functions to perform the calculations:

- `calculateTotalPower(totalWattHours, levelOfTolerance, batteryBankPower)`
- `calculateBatteryBankPower()`
- `updateLoadValue(totalWattage)`
- `calculateBackupTime(batteryVoltage, ampereHour, powerFactor, numberOfBatteries, loadW)`
- `calculateInverterCapacity(totalWattage)`
- `calculateNumSolarPanels(totalPowerGenerated, peakSunshine, panelSize)`
- `calculateLeadAcid(desiredBackupTime, totalWattage, proposedLABattery, batteryVoltage, powerFactor)`

## Contributing

Contributions to improve this project are welcome. Please open an issue or submit a pull request if you have any suggestions or fixes.
