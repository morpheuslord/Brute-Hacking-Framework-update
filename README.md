# Brute-Hacking-Framework-update-1
----------------------------------
first update.

# choco
-----------------
u can install any needed packages using choco. add this in the user_alials.cmd file:-
(choco="%CMDER_ROOT%\bin\chocolatey\choco.exe" $*)
and extract the file in the bin folder and in the ProgramData foler in c:\ drive.

# duf
------------------
to add this tool add the duf.exe file to bin and add this command to the user_alials.cmd :-
(duf="%CMDER_ROOT%\bin\duf.exe" $*).

# about-virtualbox
----------------------
if the virtual box in the program does not work u can install it using "choco" by doing "choco install virtualbox".

# about-python3
-----------------
if in some case python does not work u can install it by the help of "choco" by doing "choco install python3" .

# cygwin
----------
if u have cygwin installed in ur tool it will be there in the place u have extracted and in the c drive in the tools folder copy that to the bin folder in cygwin folder 
and config it with (cygwin="%CMDER_ROOT%\bin\Cygwin\Cygwin.bat" $*) just like how u have configured others.

# sqlmap 
-----------
dowload sqlmap and move the sqlmap folder to the E:bin/ or C:bin/ folder and add this command to the alias.cmd file (sqlmap="%CMDER_ROOT%\bin\python\python.exe" "%CMDER_ROOT%\bin\sqlmap\sqlmap.py" $*) to the file and u are good to go.

#nano usage-
------------
type :
    
    $ cd config
    
    $ nano user_aliases.cmd
* enter the command mentioned and save it.
* close the tool and restart it and u are ready to go. 
