# Select to Speak SwitchCompat AppCompat 1.3.0+ sample 
Sample project showing a bug where `SwitchCompat` states are not read using Select to Speak on Pixel phones when runing AppCompat 1.3.0+. The main branch is on AppCompat 1.4.1. To reproduce:

- Enable "Select to Speak" on a Pixel phone
- Install the App
- Start "Select to Speak" by clicking the audio icon and select the area in which the Switch is located
- Observe that no text can be read in that area
- Switch to the `appcompat-1.2` branch.
- Install the App
- Start "Select to Speak" by clicking the audio icon and select the area in which the Switch is located
- Observe that the Switch state is read
