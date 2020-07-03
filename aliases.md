## work around
- Create directory for the aliases script (eg. c:\aliases)
- Add that directory to Path environment
- Create files inside that directory with the name as the aliases with extension .bat
- Inside the file put the command to run when the alias get called

eg. create file with name `take.bat`
```
@echo off
echo.
mkdir %1
cd %1
```

that file will create folder then go to the created folder.
