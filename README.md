# FILEMONITOR #
* [[FileMonitor](https://github.com/qianyl/filemonitor/tree/master/include/filemonitor/#iterfilemonitor)] Triger the registered callback immediately when the listened file system events occured. 
* [[FileKeeper](https://github.com/qianyl/filemonitor/tree/master/include/filekeeper#iterfilekeeper)] Hot load file into your custom structure automatically.

You must include directories:

```include```, ```iter/include``` and ```macrolog/include```.

## Requirements ##
1. Compile options: --std=c++11 -pthread
2. Linux kernel: >= 2.6 (inotify)

## Log settings ##
You can get more information from [here](https://github.com/qianyl/macrolog#log-settings).
