# :skunk: WindowStash 
A simple DOS Batch File program to implement a hidden folder for your MS Windows Operating Systems.

## :label: init 

1. Clone the repo to your destination folder.
1. Open `stash.bat` and go to line 45 and replace `YOUR_PASSWORD` with your desired password.
    1.  
    ```
    43: set/p "pass=>" 
    44: 
    45: if NOT %pass%==YOUR_PASSWORD goto FAIL
    46:
    47: attrib -h -s "Control Panel.{21EC2020-3AEA-1069-A2DD-08002B30309D}"
    ```
1. Save and run `stash.bat`.
1. You should see a Folder named `Locker`.

    _**!!!!!    Run `stash.bat` to toggle `Locker` to visible or hidden    !!!!!**_

As an AdagioNeo said:
> Do not attempt to hide things which cannot be hidden

:saxophone: :musical_keyboard: :drum: :guitar: :trumpet:

