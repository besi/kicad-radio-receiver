Radio Receiver Footprint
========================


## Installation

1. Open your project folder in a terminal
2. Now execute the following commands:

        $FOLDER=lib
        git submodule add https://github.com/besi/kicad-radio-receiver $FOLDER/radio-receiver
        git submodule sync
        
3. Now in Kicad in the schematic editor add the symbol library via **Preferences >> Manage Symbol Libraries**:

        Nickname:       radio-receiver
        Library Path:   ${KIPRJMOD}/lib/radio-receiver/radio-receiver.kicad_sym

4. Now in the layout editor add the footprint library via **Preferences >> Manage Footprint Libraries...**:

        Nickname:       radio-receiver
        Library Path:   ${KIPRJMOD}/lib/radio-receiver/radio-receiver.pretty
