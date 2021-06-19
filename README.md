## Installation

1) Right click [this](https://www.dropbox.com/s/47x6vwythz6zi0o/sorry.ps1?dl=1) and run with powershell

2) Register for an account and head to [Channel Settings](https://sorry.video/users/settings/stream) and setup a channel and copy the stream key

3) go to 
 ```cmd
C:\Users\[USERNAME]\AppData\Roaming\obs-studio\plugin_config\rtmp-services 
```
right click -> properties and make it read only/hidden  
![alt text](https://i.imgur.com/ri5Fe5X.png)

4) Open OBS: Settings > Stream > Service > Show All > Sorry Video

5) Service should be Sorry Video under SHOW ALL and select a region

## Connectivity Testing

You can ping both servers if you would like to see where you have a better ping.

US-WEST

```cmd
ping us-west.sorry.video
```

US-EAST

```cmd
ping us-east.sorry.video
```
