### Shell Scripting

-  its a script/text file 
- here we write a series of command that linux shell( Bash ) will execute.
- kind of an automation

- starts with [shebang](https://www.google.com/search?q=shebang&oq=shebang&gs_lcrp=EgZjaHJvbWUyDAgAEEUYORixAxiABDIKCAEQABixAxiABDITCAIQLhivARjHARiABBiYBRiZBTIKCAMQABixAxiABDIHCAQQABiABDIKCAUQABixAxiABDIPCAYQABgKGLEDGIAEGIoFMgcIBxAAGIAEMgcICBAAGIAEMgcICRAAGIAE0gEIMjQzM2owajeoAgCwAgA&sourceid=chrome&ie=UTF-8) (#!/bin/bash)

---
#### create a new script file or open new script file
```
nano <filename>.sh
```
#### start there with shebang 
#### then to exit
```
press ctrl+o -> enter -> ctrl+x
```
#### to make it executable we have to give it permissions so

```
chmod +x <filename>.sh
```
#### to run the executable
```
./<filename>.sh
```
----
Its a 4 step process
1. create a file
2. write the script
3. make it executable
4. run it