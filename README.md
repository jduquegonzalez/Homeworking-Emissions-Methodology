# Greenhouse Gas Emissions from Home-Working

## Disclaimer

This repository is currently a **draft** and is actively being developed. The code, analysis, and conclusions are subject to further optimisation and refinement.

## Project Overview

This repository provides a comprehensive methodology for calculating and analyzing the environmental impact of homeworking. The analysis is based on a simulated survey of employees' homeworking practices, which captures detailed data on device usage, home heating and cooling, and lighting.

A key feature of this project is the **benchmarking analysis**, which compares our company's calculated emissions intensity against publicly available data from major technology and professional services firms, including **Google, Microsoft, and Accenture**. This provides crucial context for our performance and helps identify strategic opportunities for emissions reduction.

## Data

The primary dataset for the analysis is `Hypothetical_Survey_Responses.xlsx`. It contains granular, employee-level data on the following:

* **Work Patterns:** Hours per day, days per week, and weeks per year worked from home.
* **Office Equipment:** Number of desktops, laptops, and monitors, plus weekly hours on video calls.
* **Lighting:** Use of artificial lighting, type of bulbs, and energy-saving habits.
* **Heating System:** Fuel type (e.g., Gas, Electricity, Oil), additional hours of use, duration of heating season, and number of rooms heated.
* **Cooling System:** Use of cooling, system type, hours of operation, and seasonal usage.
* **Renewable Energy:** Whether the employee is on a renewable electricity tariff.

## Analysis Methodology

The analysis calculates the **incremental energy consumption and associated carbon emissions** from homeworking activities. The process is broken down as follows:

1.  **Calculate Energy Consumption (kWh):**
    * **Office Equipment:** Energy use is calculated based on the number and type of devices and the duration of video calls.
    * **Lighting:** Consumption is determined by the type of bulbs, usage patterns, and energy-saving behaviours.
    * **Heating & Cooling:** Consumption is calculated based on the specific fuel type, additional hours of use, and the area being heated or cooled. This "additionality" approach ensures we only account for energy use that occurs *because* the employee is working from home.

2.  **Calculate Carbon Emissions (tCO₂e):**
    * The calculated energy consumption (kWh) for each fuel type is multiplied by the latest **UK Government GHG Conversion Factors** to determine the final emissions in tonnes of CO₂ equivalent.
    * The model accounts for **market-based emissions** by setting the electricity emissions to zero for employees on a 100% renewable tariff.

3.  **Benchmarking:**
    * We compare our company's **carbon intensity ratios** (e.g., tCO₂e per FTE, tCO₂e per million USD revenue) against apportioned values for Google, Microsoft, and Accenture.
    * These benchmarks are derived from the companies' public environmental reports, providing a valuable industry yardstick for our performance.

## Results

The analysis provides key insights into:

* **Total Emissions:** The overall carbon footprint associated with our homeworking policy.
* **Breakdown of Emissions:** The contribution of each activity (heating, equipment, lighting) to the total footprint.
* **Benchmarking Performance:** A visual comparison of our carbon intensity against industry leaders, highlighting areas of strength and opportunities for improvement.
* **Key Influencing Factors:** The impact of variables like fuel source (gas vs. electric), renewable energy adoption, and home insulation on our emissions profile.

## Usage

This repository can be used by individuals and organisations to:

* Implement a robust methodology for assessing the environmental impact of homeworking.
* Identify the most significant drivers of homeworking emissions.
* Develop and prioritize data-driven strategies to reduce their carbon footprint.
* Compare their emissions intensity against established industry benchmarks.

## Contributions

Contributions to this repository are welcome. If you have any suggestions for improvements—particularly in refining calculations or adding new benchmarks—please feel free to open an issue or submit a pull request.

## License

This repository is licensed under the MIT License. You are free to use, modify, and distribute the code and data, as long as you acknowledge the original authors.

### Acknowledgements

This project was developed with guidance and inspiration from several key resources and organizations.

The core methodology for the survey-based calculation is adapted from research by [Green Element](https://www.greenelement.co.uk/environmental-and-sustainability-ebooks/working-from-home-emissions/), while the initial framework was inspired by the work of [EcoAct](https://info.eco-act.com/en/homeworking-emissions-whitepaper-2020?_gl=1).

The analysis adheres to the principles outlined by the [Greenhouse Gas Protocol](https://www.ghgprotocol.org/), the global standard for emissions accounting.

Special thanks to [Transputec](https://www.transputec.com/) for providing the opportunity and initial challenge that led to the development of this methodology.
