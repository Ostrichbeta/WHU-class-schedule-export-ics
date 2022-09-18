# WHU Class Schedule Export as iCS

Languages: English | [簡體中文](README-SC.md) | [繁體中文](README-TC.md)

## Changelog
### v0.90.1 - Sep 18, 2022
- Fix bugs: Fix an error when a class have multiple slices on page at the same class no. in the same day

### v0.90 - Sep 5, 2022
- Add features: now you can add an alert time before the class, and can choose diffrently for the first class in the morning, afternoon and evening.

### v0.89.2 - Sep 5, 2022
- Fix bugs: Fix a crash happened when you have a class with unspecific time

### v0.89.1 - Sep 2, 2022
- Fix bugs: Fix the problem on the timezone offsets


## Introduction

[WHU Class Schedule Export  as iCS](#) is a Tempermonky / Greasemonkey plugin which can help you export your class schedule to the calendar on your phone / pad / PC / Mac.

## Features

- Chinese conversion support
- Multi-timezone support (always return at the right time no matter which zone your device is in)
- No data upload, all the data is processed on your device

## How to Use

1. Open your Teaching Administration System, and click "```Show my schedule (学生课表查找)```" button.

![](res/main_menu.png)

2. If you have installed the plugin, there will be a new button called "```Export as iCS (导出iCS)```". Choose what data you want to show on your calendar by clicking the "```⚙```" icon on the left and selecting the items displayed on the screen. **The schedule WON'T export if you unselect the "```Time (时间)```" item!** After that, click the "```Export as iCS (导出iCS)```" button to open the export panel.

![](res/step1.png)

3. Select the first day of your term and your preferred language, and click the "```Export (导出)```" button.

![](res/step2.png)

Now your schedule is saved as an iCS calendar. You can import the file to your calendar app.

## Libaries Used

- [jQuery](https://jquery.com/)
- [Bootboxjs](http://bootboxjs.com/)
- [OpenCC-js](https://github.com/nk2028/opencc-js)
- [ics.js](https://github.com/nwcell/ics.js)
  
## Special Thanks

- [Eric Lian](https://github.com/ExerciseBook)