# Super Animal Royale – Pearl Drop Simulator

A web-based simulator for calculating pearl drop rates in Super Animal Royale. This tool helps you estimate how many pearls of each type you'll receive based on your daily clam collection and custom drop probability settings.

## Why This Tool Exists

As a dedicated Super Animal Royale player, I built this simulator to help plan my pearl farming strategy. The game's pearl drop rates can be frustratingly rare (especially Black and Gold pearls!), and it's hard to know if all that grinding is worth it without seeing what you might actually get.

This tool answers questions like:
- **"If I collect 150 clams per day for 50 days, how many Black Pearls can I realistically expect?"**
- **"How long will it take me to get enough pearls for that cosmetic I want?"**
- **"Is it worth doing multiple island loops per day, or should I focus on other activities?"**

By testing out different scenarios with the actual drop rates, you can see ahead of time what kind of results you might get and decide if the grind is worth your time.

## Features

- Simulate pearl drops across multiple days
- Customizable drop probability rates for each pearl type (Black, Gold, Purple, Blue, Green, White)
- Visual chart showing pearl distribution
- Day-by-day breakdown of results
- Total summary statistics across all simulated days

## Download and Setup

### Step 1: Download from GitHub

1. Navigate to the GitHub repository
2. Click the green **"Code"** button
3. Select **"Download ZIP"** to download the repository as a ZIP file
4. Save the ZIP file to your desired location (e.g., `Downloads` folder)

### Step 2: Extract the ZIP File

1. Locate the downloaded ZIP file (e.g., `PearlSimulator-main.zip`)
2. Right-click on the ZIP file
3. Select **"Extract All..."** (Windows) or use your preferred extraction tool
4. Choose a destination folder (e.g., `C:\Projects\PearlSimulator` or `Documents\PearlSimulator`)
5. Click **"Extract"** to unzip the files

### Step 3: Run the Simulator

1. Navigate to the extracted folder
2. Locate the file `index.html`
3. Double-click the file to open it in your default web browser
   - Alternatively, right-click the file and select **"Open with"** → choose your preferred browser (Chrome, Firefox, Edge, etc.)

That's it! The simulator will load in your browser and you can start using it immediately.

## How to Use

1. **Set Simulation Parameters:**
   - Enter the number of clams you collect per day
   - Set how many days you want to simulate
   - Configure clams on island (default: 41) - the number of clams available on the island
   - Configure minutes per loop (default: 5) - the time it takes to complete one loop around the island

2. **Adjust Drop Chances (Optional):**
   - Modify the probability values (0-1) for each pearl type
   - Default values represent rare drop rates

3. **Run Simulation:**
   - Click the **"Run Simulation"** button
   - Scroll down to view day-by-day results
   - Check the summary box for total statistics and visual chart

## Requirements

- A modern web browser (Chrome, Firefox, Edge, Safari, etc.)
- No additional software or dependencies needed
- Works offline once downloaded

## Notes

- The simulator assumes perfect island loops with all clams untouched
- Default settings assume 41 clams on island and 5 minutes per loop (configurable)
- Results represent idealized outcomes without player interference
- All image files (black.png, gold.png, purple.png, blue.png, green.png, white.png, empty.png) must be in the same directory as `index.html` for the simulator to work correctly
- You can customize the number of clams on island and time per loop to match your actual gameplay

## File Structure

When you download and extract the repository, your folder structure will look like this:

```
PearlSimulator/              (or PearlSimulator-main/ if downloaded as ZIP)
├── index.html               (Main application file - open this in your browser)
├── favicon.ico              (Favicon icon file)
├── README.md                (This documentation file)
├── black.png                (Black pearl image)
├── gold.png                 (Gold pearl image)
├── purple.png               (Purple pearl image)
├── blue.png                 (Blue pearl image)
├── green.png                (Green pearl image)
├── white.png                (White pearl image)
└── empty.png                (Empty clam image)
```

**Important:** All files must be in the same folder (root directory). The simulator requires `index.html`, `favicon.ico`, and all image files to be in the same location for everything to work correctly.

## Troubleshooting

- **Images not showing?** Make sure the pearl image files (black.png, gold.png, etc.) are in the same folder as `index.html`
- **Page not loading?** Try opening the HTML file with a different browser
- **Results look incorrect?** Verify that your drop probability values sum to less than 1.0
