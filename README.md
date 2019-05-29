## Bloc / Thinkful Grading Firefox Extension

Firefox extension for graders to auto fill with a grading signature and greeting

__Note:__ Based on the 

[https://github.com/nikibrown/bloc-grading-chrome-extension](Chrome Extension)

### Video walk through

[http://nikib.ro/wn/screenshots/grading-chrome-extension-update.mp4](http://nikib.ro/wn/screenshots/grading-chrome-extension-update.mp4)

### Installation instructions

- Download or clone this repo
- In Firefox go to [about:debugging#/runtime/this-firefox](about:debugging#/runtime/this-firefox)
- Click on "Load Temporary Add-on..."
- Browse to and select any file in the extension directory (I chose the manifest.json)
- Thats it!
- To refresh the extension (when you pull from the repo or make changes) you can click on the reload button.

### Usage

- Open the options by clicking on the chrome extension icon.
- Enter your name and the program you're grading.
![extension options](https://t.gyazo.com/teams/leovegas/7753d89a481ac07be48a342f8d060219.png)
- Go to any submission that you've claimed from the grading queue and the snippet will be added
 on page load. It will automatically adapt to the program you selected.
- Changing the program while grading will automatically re-populate the text field, this is 
useful to avoid refreshing the page, but be careful as it will override anything you wrote before.
- You can also customize the intro message from the default to your own.
