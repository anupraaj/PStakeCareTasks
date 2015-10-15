# PStakeCareTasks

### Task 1: Process Schedule JSON

File: process-schedule-json.html

```
Sample input1:
{"sun":[],"mon":[{"from":1030,"to":1400},{"from":1830,"to":2300}],"tue":[{"from":1030,"to":1400},{"from":1830,"to":2300}],"wed":[{"from":1030,"to":1400},{"from":1830,"to":2300}],"thu":[{"from":1030,"to":1400},{"from":1830,"to":2300}],"fri":[{"from":1030,"to":1400},{"from":1830,"to":2300}],"sat":[]}

Sample output1:
"10:30 AM to 2:00 PM, 6:30 PM to 11:00 PM except Sunday and Saturday"
```



```
Sample input2:
{"sun":[{"from":0,"to":2359}],"mon":[{"from":0,"to":2359}],"tue":[{"from":0,"to":2359}],"wed":[{"from":0,"to":2359}],"thu":[{"from":0,"to":2359}],"fri":[{"from":0,"to":2359}],"sat":[{"from":0,"to":2359}]}

Sample output2:
"24X7"
```



```
Sample input3:
{"sun":[],"mon":[{"from":930,"to":1330},{"from":1700,"to":2100}],"tue":[{"from":930,"to":1330},{"from":1700,"to":2100}],"wed":[{"from":930,"to":1330},{"from":1700,"to":2100}],"thu":[{"from":930,"to":1330},{"from":1700,"to":2100}],"fri":[{"from":930,"to":1330},{"from":1700,"to":2100}],"sat":[{"from":930,"to":1330},{"from":1700,"to":2100}]}

Sample output3:
"9:30 AM to 1:30 PM, 5:00 PM to 9:00 PM except Sunday"
```

