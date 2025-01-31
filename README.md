# Greenhouse Gas Emissions from Home-Working

## Disclaimer

This repository is currently a **draft** and is actively being developed. I am aware that the code and analysis may need further optimisation and refinement.

## Project Overview

This repository contains code and data for analysing the environmental impact of homeworking. The analysis is based on a simulation of a survey of employees' homeworking practices and energy consumption habits.

## Data

The dataset used for the analysis is stored in the file `Hypothetical_Survey_Responses.xlsx`. It contains information about:

*   Respondent ID
*   Hours/Day
*   Days/Week
*   Weeks/Year
*   Desktops
*   Laptops
*   Monitors
*   Video Call Hours/Week
*   Lights On
*   Light Type
*   Switch Off
*   Renewable Energy
*   Additional Heating
*   Heating Hours/Day
*   Heating Months/Year
*   Heating Area
*   Heating Fuel
*   Use Cooling
*   Cooling Type
*   Cooling Hours/Day
*   Cooling Months/Year
*   Cooling System Adjustment

## Analysis

The analysis calculates the energy consumption and carbon emissions associated with homeworking activities, including:

*   Lighting: Energy consumption based on the number of devices, type of bulbs, and usage hours.
*   Heating and Cooling: Energy consumption based on the type of fuel, usage hours, and area heated or cooled.
*   Office Equipment: Energy consumption based on the number and type of devices (desktops, laptops, monitors).
*   Video Calls: Energy consumption based on the hours spent on video calls.

The total emissions are calculated by multiplying the energy consumption by appropriate conversion factors and then summing across all activities.

## Results

The analysis provides insights into the following:

*   Total emissions: The overall carbon footprint associated with homeworking.
*   Breakdown of emissions: The contribution of each activity to the total emissions.
*   Factors influencing emissions: The impact of variables like the number of devices, usage hours, and energy efficiency measures on emissions.

## Usage

This repository can be used by individuals and organisations to:

*   Assess the environmental impact of homeworking.
*   Identify areas for improvement in energy efficiency.
*   Compare their emissions with benchmarks.
*   Develop strategies to reduce their carbon footprint.

## Contributions

Contributions to this repository are welcome. If you have any suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This repository is licensed under the MIT License. You are free to use, modify, and distribute the code and data, as long as you acknowledge the original authors.

## Acknowledgements

This project is inspired by the work of [EcoAct](https://info.eco-act.com/en/homeworking-emissions-whitepaper-2020?_gl=1) and the [Greenhouse Gas Protocol](https://www.ghgprotocol.org/). The methodology is based on research by [Green Element](https://www.greenelement.co.uk/environmental-and-sustainability-ebooks/working-from-home-emissions/), where a comprehensive survey model for calculating emissions from working from home can be found.
