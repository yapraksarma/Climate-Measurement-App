# Climate Tracking System

A Java application for tracking and analyzing climate data across different cities and countries. The system monitors various climate measurements including temperature, humidity, wind speed, and radiation absorption.

## Features
- Temperature tracking in multiple units (Celsius, Fahrenheit, Kelvin)
- Wind speed measurements (meters/second and km/hour)
- Humidity percentage monitoring
- Radiation absorption analysis
- Felt temperature calculations
- Historical data storage (2020-2022)

## Project Structure
- `Location.java`: Abstract base class for locations
- `City.java`: City-specific climate data management
- `Country.java`: Country-wide temperature tracking
- `ClimateMeasurement.java`: Base class for all climate measurements
- `Temperature.java`: Temperature measurement in multiple units
- `Humidity.java`: Humidity tracking
- `WindSpeed.java`: Wind speed measurements
- `RadiationAbsorption.java`: Radiation absorption tracking
- `ClimateRecord.java`: Main data storage and retrieval
- `ClimateApp.java`: Main application logic
- `FileIO.java`: File operations for data persistence

## Getting Started
1. Clone the repository
2. Compile the Java files
3. Run ClimateApp
