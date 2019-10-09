# Power Purchase Agreement (PPA) Cost Analysis Tool

This tool evaluates the financial performance of a PPA for solar photovoltaic systems. It was created by City of San Diego staff to monitor the financial performance of PPAs within their portfolio and to also model future PPA costs against current commercial utility power.

## Getting Started

These instructions will allow you to run the calculator on the web. 

### Prerequisites

In order to run a calculation, you will need a few things:

* 15-Minute Interval Utility Data 
* 15-Minute Interval Solar Production Data (Real or Simulated)

## Running the tests

The tool will allow you to specify any time period, as long as the interval data includes those dates. 

If the tool is being used to track an existing PPA with real consumption and production data, it is recommended that a single month is analyzed at a time to be compared against utility billing information for that time period. 

### Calculator Inputs

A screenshot of the tool is provided below, followed by a description of each input.

![enter image description here](https://github.com/bryanolson/PPACalculator/blob/master/PPA_Image.png?raw=true)

```
Start Date, End Date 
```
* Describes the date range to be analyzed
```
Holiday
```
* If a holiday is within billing period, enter the date of the holiday in MM/DD/YYYY format. In the assumed tariff, a holiday is calculated with the entirety of the day billed in off-peak time-of-use .
```
Load Profile
```
* 15-Minute load data is required. The format of the load data is shown in the screenshot below. The time period of the load profile is irrelevant, as long as the requested Start Date and End Date have data available.
