# fat-dash - dashboard for FPS Aim Trainer
Track your own progess in FPS Aim Trainer. Analyze your challenges, scenarios and time periods by importing csv files which are created by the game for each challenge.

![fat_dash_picture](https://raw.githubusercontent.com/fat-dash/fat-dash/master/fat_dash_picture.jpg)

## Usage

### Upload some challenge files
1. Click on the upload icon on the top left.
2. Select all challenge files created from the game. E.g. `<Your steam lib folder>\steamapps\common\FPSAimTrainer\FPSAimTrainer\stats`
3. Crunch some numbers.

### Widgets

#### Challenge History
See your most recent challenges and compare measures like score with the scenario average. Challenges can be filtered by date and scenario - just click on the filter icon to the right of the table header name. Choose and switch between a measure to display for all challenges.

#### Time Line
Track your progress on some measure over a period of time. Filter by scenario and measure by clicking somewhere on the widget header bar. See Graph Controls for further details.

### Graph controls
- Drag to zoom in and double-click to return to the original graph. Alternative: Zoom and Autoscale buttons at the top right of widget.
- Drag the graph corners to zoom along one axis
- Double-click x or y axis to autoscale on a single axis
- Hover over a graph point to get its coordinates
- Hold <kbd>shift</kbd> + Left Mouse to move around in the graph. Alternatives: Drag an axis or press the pan-button at the top right of the graph 

## Optimizations
Currently, imported csv files are not saved (yet) - after closing the tab, next time files are to be reimported. Simple solution: Keep the tab open, if you want to import more files. Most likely file import speed is limited by your disk performance. Saving all challenge files on a SSD partition can really benefit import time. Also, reimporting files should happend much faster second time due to disk cache.

## Compatibility
### Browser
Just use an up-to-date browser. Tested with
- Firefox 63 - should work with any decent version 55+ or even older
- Chromium 73 - should work with any half decent Chrome version
- Don't get your hands dirty with IE 😉. Also I am not sure concerning Safari browser.

### csv-files support
- starting at Game Version 1.0.2
- only challenges (not tested with free-to-play sessions)

## Disclaimer
This is a community project (not from the official author).
