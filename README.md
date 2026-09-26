# DayZ export preset for ArmorPaint

An export preset for [ArmorPaint](https://armorpaint.org/) that produces textures compatible with DayZ.

## Installation

1. Open ArmorPaint
2. Open `Export Textures`
3. Go to the `Presets` tab
4. Click `Import`
5. Select `dayz.json`

## Usage

1. Open `Export Textures`
1. Select the imported `dayz` preset
2. Export textures as PNG
3. ArmorPaint will write files named:
   - `<name>_co.png`
   - `<name>_nohq.png`
   - `<name>_as.png`
   - `<name>_smdi.png`
   - `<name>_em.png`

All channels are always exported, even if they are empty. Check your outputs and replace empty channels with a
generated stage (e.g. `texture="#(argb,8,8,3)color(1,1,1,1,AS)") in the rvmat for efficiency and space savings.
