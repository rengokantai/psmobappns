#### psmobappns
######14 vs code extension nativescript
F1 > extension  
ext install nativescript  

######15
configure workspace:settings
```
{
  "files.exclude":{
    "**/*.js.map":true
  }
}
```
######18 commands
```
tns create/platform/install/run/debug/livesync
```
######21 define pages
setting initial page
```
import application = require("application")
application.start({moduleName:"main"})
```

######22 start.
```
tns create ke --template tns-template-blank
```
