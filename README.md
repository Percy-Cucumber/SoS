---
---

# SoS Applets by Percy_Cucumber
These are a series of applets to be used alongside the mobile game State of Survival. All code is written in Python 3 using Jupyter Notebook, and shared using GitHub and Binder for free unrestricted public use. Permission from the author required for any commercial use.

Launch Binder To Edit/Execute Jupyter Files In Browser Here -->  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Percy-Cucumber/SoS/HEAD)

---
---

# How To Use
Each individual Jupyter file is clearly annotated, and was designed to be as simple and intuitive as possible so that it may be edited and used by people who may not necessarily be technologically proficient. Just follow the instructions below to get the desired files open within your web browser:
1) Click on the `Launch Binder` button -->  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Percy-Cucumber/SoS/HEAD).
2) You will be redirected to a binder page with a non-interactive preview of my GitHub SoS Repository on nbviewer. Just wait patiently for a server to be started for you. Your binder will open automatically when it is ready (this may take a bit depending on your device and network connection).
3) Once you've been redirected to your binder, you will find yourself looking at Percy_Cucumber's SoS Repository using Jupyter. Here you will find this readme document alongside all of the SoS applets (each as a .ipynb Jupyter file). Simply click on whichever Jupyter file you wish to open. A description of all available applets can be found below.
4) After you have opened an applet of your choice, insert your desired values at the appropriate locations within the code (every section is labeled using `# Commented Headers`. All values to be manually inserted are found in the top part of the code, and have been assigned with a default value of 0.
5) When you are content with the values you've inputted, press `shift+enter` to run the code. Alternatively you can use the `▶︎|Run` button in the toolbar, or either the `Run Cells` or `Run All` commands under the `cells` dropdown menu. Either way, the results will be printed inderneath the cell that has the code in it).
6) At any point you may go back into the cells to change out any of the numerical values, though you will need to re-run the code to get updated results printed (see previous step).
If you need any farther assistance for which numerical values to update within each applet, check the applet's description below:

---
---

# Description of Applets
## SoS-1
**This applet was created for eased calculation of speedup times for events such as Alliance Throwdown challanges.**
### Input:
- number of speedups currently in your posession that are spefific to the task that you wish to speedup (ie. building speedups for speeding up construction)
- number of general speedups in your posession
- how many speedups you need / how much time you need sped up (optional)
### Output:
- total value of your specific speedups in minutes
- total value of your general speedups in minutes
- total value of all your speedups in minutes
- total value of speedups you need to finish the task you defined in minutes
- how many speedups are you missing to finish this task in minutes (if the printed result is negative it means you have more speedups than you need, and it is telling informing you how many minutes of excess speedups you have)

## SoS-2
**Applet for calculating how much plasma you need to reach the next star level on a building upgrade.**
### Input:
- plasma cost of upgrading one level of that building
- how many levels you have already upgraded
- amount of plasma in backpack (optional)
### Output:
- plasma required to reach next star level of that building
- how much more plasma you are missing to reach next star level of that building (assuming you also added the amount of plasma currently in your backpack)

## SoS-3
**Applet for calculating how much plasma you've spent, as well as how much more you will need to spend in order to reach max level of all buildings + research.**

This applet is already setup to accomodate uo to 10 plasma ranks, even though only five currently exist. Currently anything past plasma level 5 can NOT affect your results, though further plasma values will be added to these placeholder slots as soon as more plasma levels are added to State of Survival.

***NOTE: APPLET IS NOT YET FULLY COMPLETE***

### Input:
- how many levels of each building upgrade have been completed
- what plasma research has been completed (not yet implemented)
### Output:
- plasma required to max all buildings
- plasma spent on upgrading buildings thus far
- plasma still required to finish all building upgrades

- plasma required to max research (not yet implemented)
- plasma spent on research thus far (not yet implemented)
- plasma still required to finish all research (not yet implemented)
- overall plasma cost up upgrading everything (not yet implemented)
- total plasma spent across all sources (not yet implemented)
- plasma still required to max everything (not yet implemented)

---
---
