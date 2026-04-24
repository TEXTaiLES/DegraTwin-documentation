# Usage

This page explains how to use the DegraTwin application to run a textile degradation simulation.

---

## 1. Select simulation parameters

Use the sidebar to configure the simulation.

### Fabric type

Choose the textile material:

- Cotton
- Silk
- Wool

### Projection years

Select how many years the degradation simulation should cover.

### Harm component weights

Adjust the importance of each degradation factor:

- Mechanical harm
- Chemical harm
- Biological harm
- Light-related harm

### Light background option

Choose whether light exposure should be ignored or evaluated against a black or white background.

### Dose limit

Set the dose threshold used in the simulation.

---

## 2. Load data

Click **Load data** to import environmental sensor data.

If API data is enabled, the application retrieves humidity and temperature readings from the external data source.

If the API request fails, the application automatically switches to fallback sample data.

---

## 3. Run the simulation

Click **Run simulation**.

The application will:

- calculate the average temperature
- evaluate the environmental conditions
- simulate degradation scenarios
- generate plots and output data

---

## 4. View the results

After the simulation is complete, the application displays:

- Sensor preview table
- Relative humidity comparison plot
- Degradation by scenario plot
- JSON output summary

---

## Typical workflow

```text
Select parameters → Load data → Run simulation → Review results → Export JSON