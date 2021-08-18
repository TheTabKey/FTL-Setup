## Installation

1) Right click [this](https://www.dropbox.com/s/y06vv7iqahf7w9p/sorry.ps1?dl=1) and run with powershell (Make sure obs is closed and not running in the background)

2) Register for an account and head to [Channel Settings](https://sorry.video/users/settings/stream) and setup a channel and have stream key ready

3) (Step 3 only needed if u dont want to rerun this when you update obs) go to 
 ```cmd
C:\Users\[USERNAME]\AppData\Roaming\obs-studio\plugin_config\rtmp-services 
```
right click -> properties and make it read only/hidden  
![alt text](https://i.imgur.com/ri5Fe5X.png)

4) Open OBS: Settings > Stream > Service > Show All > Sorry Video

## Without file replacement
1) 
```cmd
ftl://sorry.video
```
![alt text](https://i.imgur.com/GKvCVnw.png)

2) 
![alt text](https://i.imgur.com/998nIOT.png)
