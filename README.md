# English-Mathematical-Keyboard
English (UK) Mathematical Keyboard Code for Ubuntu 24.04.3 LTS

## Setup Instructions
1. Copy `gbMAT.c` to `/usr/share/X11/xkb/symbols` folder

2. In `/usr/share/X11/xkb/rules/evdev.lst` and `/usr/share/X11/xkb/rules/base.lst`, add the following under `! layout`:
   
   ```gbMAT		  English (UK) Mathematical```
  

3. In `/usr/share/X11/xkb/rules/evdev.xml` and `/usr/share/X11/xkb/rules/base.xml`, add the following within `<layoutList>`:

    ```
    <layout>
      <configItem>
        <name>gbMAT</name>
        <shortDescription>gbMAT</shortDescription>
        <description>English (UK) Mathematical</description>
        <countryList>
          <iso3166Id>GB</iso3166Id>
        </countryList>
        <languageList>
          <iso639Id>eng</iso639Id>
        </languageList>
      </configItem>
      <variantList/>
    </layout>
    ```
## Other info
Please [email me](mailto:Reya.Khan\@outlook.com) if you encounter any issues or have any suggestions! Note I'm fairly new to Linux and GitHub.
