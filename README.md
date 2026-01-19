# ColouredMusic

Turn MIDI songs into colorful visualizations.

## What This Does

Converts MIDI files to colored visualizations by mapping musical notes to the visible light spectrum.

- **Horizontal position**: Time (left to right)
- **Color**: Musical pitch (low notes = red, high notes = blue)
- **Width**: Note duration

## Files

- `midi_to_csv.ipynb` - Main notebook (run this!)
- `example_converted.csv` - MIDI file in CSV format
- `dataframe.csv` - Processed note data
- `Plots/` - Generated visualization files

## Example Output

<img src="Plots/all_tracks_notes_plot.png" width="600">

*All instrument tracks stacked vertically, showing the full composition with colors representing pitch.*

## Quick Start

1. Install dependencies: `pip install py_midicsv pandas matplotlib`
2. Open Jupyter: `jupyter notebook midi_to_csv.ipynb`
3. Run all cells
4. Find your visualizations in the `Plots/` folder!

That's it!
