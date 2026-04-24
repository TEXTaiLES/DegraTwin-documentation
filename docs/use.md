### `docs/use.md`

Εδώ βάζεις τις οδηγίες χρήσης.

```md
# Usage

## Application flow

### Step 1: Select simulation parameters

The user selects the simulation settings from the sidebar:

- Fabric type: Cotton, Silk, or Wool
- Projection years
- Harm component weights
- Light background option
- Dose limit
- API data option
- Number of fallback sample points

### Step 2: Load data

Click **Load data**.

If API data is enabled, the application retrieves sensor readings and processes them.

If the API request fails, the application switches to fallback sample data.

### Step 3: Run simulation

Click **Run simulation**.

The application computes the average temperature and runs the full degradation simulation.

### Step 4: View outputs

The application displays:

- Sensor preview table
- Relative humidity comparison plot
- Degradation by scenario plot
- Output JSON summary