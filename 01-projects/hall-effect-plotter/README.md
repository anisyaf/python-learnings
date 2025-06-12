# Hall Effect Experiment Plots

This project contains Python scripts that visualize experimental data from Hall Effect-related measurements. The goal is to analyze how Hall voltage and resistance vary with different physical parameters such as magnetic flux, temperature, and current.

## 📊 Graphs Included

1. **Hall Voltage vs Control Current**  
   - Visualizes the relationship between applied control current and the resulting Hall voltage.
   - Data: Manually input into script.
   - Output file: `hall_voltage_vs_current.png`

2. **Change in Resistance vs Magnetic Flux**  
   - Plots normalized resistance change `(R - Ro)/Ro` as a function of magnetic field strength.
   - Data: Manually input.
   - Output file: `resistance_vs_flux.png`

3. **1/Vs vs 1/T**  
   - Uses data from `GRAPH3_EXP2.csv` to show inverse signal voltage vs inverse temperature.
   - Output file: `inverse_vs_vs_temperature.png`

4. **ln(1/Vs) vs 1/T**  
   - Uses data from `Book1.csv` to plot the natural logarithm of inverse signal voltage vs inverse temperature.
   - Output file: `ln_inverse_vs_vs_temperature.png`

5. **Hall Voltage vs Magnetic Flux**  
   - Plots Hall voltage as a function of magnetic flux using data from `GRAPH4_EXP2.csv`.
   - Output file: `hall_voltage_vs_flux.png`

6. **Hall Voltage vs Temperature**  
   - Uses data from `GRAPH5_EXP2.csv` to show how Hall voltage varies with temperature.
   - Output file: `hall_voltage_vs_temperature.png`
     
## ▶️ How to Run

Make sure you have `matplotlib` and `pandas` installed. Then run:

```bash
python hall_effect_plots.py
