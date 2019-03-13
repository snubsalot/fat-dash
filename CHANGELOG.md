Test versions for the next release (with version number xxx-next) can be found here: https://fat-dash.github.io/next/

---

## 0.7.0-alpha (19-03-13)
- Add kill count as measure
- Time Line: 
  - Add option to choose between challenge date and challenge number for x-axis
  - Per default challenge number for x-axis is selected (before it was challenge date) to display a uniform, even distribution
- Fix measures for invincible scenarios
  - Before, no values were shown for some measures like accuracy and efficiency
  - Now, all measures are collected from the weapon and challenge statistics 
- Change the measure names slightly in order to reflect their origin more accurately

## 0.6.1-alpha
- Fix unnoticed <kbd>o</kbd> key press in input fields. <kbd>o</kbd> was hidden by <kbd>Ctrl</kbd> +<kbd>o</kbd> hotkey to open the file dialog quickly.

## 0.6.0-alpha
- Add Omit zero value scores csv Import Filter
  - The filter is activated automatically, but can be disabled in upload menu

## 0.5.0-alpha (19-03-07)
- Add Date filter for Time Line Widget
- Fix circurlar coordinates in Time Line chart, which sometimes occured

## 0.4.0-alpha
- Add scenario highscore fields in Challenge History Widget
  - Show scenario Average, min and max scenario measure with percent diff comparisons to challenge measure
  - Add checkboxes to choose visibility of min, max and average scenario measures
- Add scenarioName filter for Playcount and Oldest Highscores Widget
- Ease up TimeLine Chart by removing aggregate form field value 
- Return scenarioNames in select form sorted 
- Add challenge markers to Time Line graph
- UI improvements/Fixes

## 0.3.1-alpha
* Make loading icon animation smoother

## 0.3.0-alpha
* Add Form status bar to Time Line Widget
* Fix an error that prevents finishing the file upload if many files are selected
* Various UI improvements

## 0.2.0-alpha
* Optimize challenge file upload performance

## 0.1.1-alpha
* Fix PlaceHolder issue in Challenge History Widget (3138531)
* Fix various Draw/Format issues

## 0.1.0-alpha
* Initial release
