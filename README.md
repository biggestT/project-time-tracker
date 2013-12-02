project-time-tracker
====================

Bash run shellscript for tracking time spent on different task in a project and output it to a markdown logfile

## Usage:

### initiate timetracking for the current project folder
After cd into the root folder of the project you want to track:
```bash
ptt init
```
ptt should always be called from the root folder of the project that you are timetracking

### start/resume timetracking
```bash
ptt start
```

### pause timetracking
```bash
ptt paus
```

### stop timetracking
```bash
ptt stop
```
The timetracker will then ask you what task you worked on and then add a new entry to the TIMELOG.md file.
It will also recalculate the total time spent on the current project based on the entries in the TIMELOG.md file.

### show current state of the timetracker
```bash
ptt log
```
