### Steps to reproduce:
Created a minimum app to reproduce the error. Clone the following app wwjnkjdfsnkjsdnf. 

Requirements: 
- node 16.10.0

Setup the app using 

```cmd
npm i
```

Start using app using

```cmd
npm run start
```

While NVDA is running.

Tab on the select component on screen and press enter to open menu.

### Actual behavior:
Unable to navigate the menu with the up and down arrows - you must first press enter before being able to navigate the menu.

### Expected behavior:
When the menu has been opened you should be able to navigate said menu with the up and down arrows.

Expected behavior occurs when NVDA is not running.

### NVDA logs, crash dumps and other attachments:
N/A

### System configuration
#### NVDA installed/portable/running from source:
NVDA install on windows
#### NVDA version:
2022.2.1
#### Windows version:
Windows 11 Business 21H2
#### Name and version of other software in use when reproducing the issue:
N/A
#### Other information about your system:
N/A
### Other questions
#### Does the issue still occur after restarting your computer?
Yes
#### Have you tried any other versions of NVDA? If so, please report their behaviors.
Reproduced on 2021.3.5 
#### If NVDA add-ons are disabled, is your problem still occurring?
No add-ons installed 
#### Does the issue still occur after you run the COM Registration Fixing Tool in NVDA's tools menu?
Yes