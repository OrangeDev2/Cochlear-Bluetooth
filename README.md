### October 11, 2023 Update: I'm getting a Phone Clip accessory, which acts as a middleman to link multiple versions of Cochlear Processors with Bluetooth devices like PC.  Nuclesus 7 with BLE itself only supports some iOS and Android devices.

![New Project (4)](https://github.com/Saboor-Malik/cochlear-bluetooth/assets/47803678/e406af1c-b8f0-488d-97db-116f4b163708)

### In my project, I'm trying to establish a connection with my processor Cochlear Nucleus 7 through Bluetooth protocol (Using SimplePYBLE Library), similar to how the Nucleus Smart app does.  
![image](https://github.com/Saboor-Malik/cochlear-bluetooth/assets/47803678/89072867-a8a4-4319-a746-dbab879c36ea)

### It seems like my cochlear processor is not in discoverable mode or It might not be the bluetooth protocol that has to detect my processor.
![New Project (5)](https://github.com/Saboor-Malik/cochlear-bluetooth/assets/47803678/3818c570-b6b3-42d5-a819-e802decbf80f)

Bluetooth protcol and possibly pushed to settings by Nucleus Smart app (Mobile app) is only method I know that can connects to my cochlear processor.

Note: Cochlear Processor is not in discoverable mode, awaiting Cochlear Americans response.

    What I know is,

    Nucleus smart has to establish an connection in some way then push it to the bluetooth settings on phone
    Processor's not in discoverable mode, maybe on Android only?  i.e React native app
    I looked up the specs for my processor, it says it has Bluetooth Smart (called BLE now), the python library should work but it's just not in discoverable by Windows?

Resources:

https://learn.sparkfun.com/tutorials/bluetooth-basics/all

https://github.com/Saboor-Malik/SimpleBLE
