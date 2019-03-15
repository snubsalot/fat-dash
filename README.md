# fat-dash - dashboard for FPS Aim Trainer

Track your own progess in FPS Aim Trainer. Analyze your challenges, scenarios and time periods by importing csv files which are created by the game for each challenge.

![fat_dash_picture](https://raw.githubusercontent.com/fat-dash/fat-dash/master/fat_dash_picture.jpg)

## Getting started

1. Click on the upload icon on the top left.
2. Select all challenge files created from the game. E.g. `<Your steam lib folder>\steamapps\common\FPSAimTrainer\FPSAimTrainer\stats`
3. Crunch some numbers.

## Widgets

### Challenge History

See your most recent challenges and compare measures like score with the scenario average. Challenges can be filtered by date and scenario - just click on the filter icon to the right of the table header name. Choose and switch between a measure to display for all challenges.

### Time Line

Track your progress on some measure over a period of time. Filter by scenario and measure by clicking somewhere on the widget header bar. See Graph Controls for further details.

### Graph controls

- Drag to zoom in and double-click to return to the original graph. Alternative: Zoom and Autoscale buttons at the top right of widget.
- Drag the graph corners to zoom along one axis
- Double-click x or y axis to autoscale on a single axis
- Hover over a graph point to get its coordinates
- Hold <kbd>shift</kbd> + Left Mouse to move around in the graph. Alternatives: Drag an axis or press the pan-button at the top right of the graph

## Upload settings

In the game under Game Options, you can set the Statistics Export mode. Recommended values are:  

![challenge_wins](https://user-images.githubusercontent.com/45684225/54418653-d24a3d00-4705-11e9-9d37-bed3ce418c9e.png)  
If the scenario score win value is not reached (can only be changed by scenario editors), there will be no csv file emitted. There might be scenarios where a default win value of 1000 is kept, but such a score actually cannot be reached. Here is where "Any challenge" becomes interesting.

![any_challenges](https://user-images.githubusercontent.com/45684225/54418487-5ea83000-4705-11e9-939e-93308da7d712.png)  
Always csv files are emitted, even if the challenges are aborted. Aborted challenges have a zero value score. 

To get rid of aborted challenges, **per default** all challenges with a zero value score are filtered out as its suitable in almost all situations. If you want to change that, there is an upload option:
![image](https://user-images.githubusercontent.com/45684225/54419994-26a2ec00-4709-11e9-9538-16a172342201.png)

> Info: Aborted csv files (zero value score) do not contribute to the play count of a scenario per default.

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
