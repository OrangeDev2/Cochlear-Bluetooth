![New Project (4)](https://github.com/Saboor-Malik/cochlear-bluetooth/assets/47803678/e406af1c-b8f0-488d-97db-116f4b163708)

### In my project, I'm trying to establish a connection with my processor Cochlear Nucleus 7, similar to how the Nucleus Smart app does.  
### Bluetooth protcol and possibly pushed to settings by Nucleus Smart app (Mobile app) is only method I know that can connects to my cochlear processor.
![image](https://github.com/Saboor-Malik/cochlear-bluetooth/assets/47803678/89072867-a8a4-4319-a746-dbab879c36ea)

### I'm using the SimplePyBLE library to scan the Bluetooth/BLE devices around me and connects to my cochlear processor at the first stage.
### It seems like my cochlear processor is not in discoverable mode or It might not be the bluetooth protocol that has to detect my processor.
![image](https://github.com/Saboor-Malik/cochlear-bluetooth/assets/47803678/942a000b-5354-4120-a00c-80df8d375aa2)

Note: Cochlear Processor is not in discoverable mode, awaiting Cochlear Americans response.

    What I know is,

    Nucleus smart has to establish an connection in some way then push it to the bluetooth settings on phone
    Processor's not in discoverable mode, maybe on Android only?  i.e React native app
    I looked up the specs for my processor, it says it has Bluetooth Smart (called BLE now), the python library should work but it's just not in discoverable by Windows?
