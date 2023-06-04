<h3 align="center">
<img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/header-image.png?raw=true" alt="stacks"/>
</h3>


# About

You can easily control your smartphone from your smart watch by using the Automate and Macrodroid application in a compatible way.

# Requirements

* Android Smartphone 
* Wear OS Smartwatch 
* [Automate](https://play.google.com/store/apps/details?id=com.llamalab.automate) and [Macrodroid](https://play.google.com/store/apps/details?id=com.arlosoft.macrodroid) App

# Installation 
**1** - Install [Automate](https://play.google.com/store/apps/details?id=com.llamalab.automate) and [Macrodroid](https://play.google.com/store/apps/details?id=com.arlosoft.macrodroid) App on Smartphone
<details>
  <summary>Screenshot</summary>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/1.png?raw=true" alt="stacks"/>
</details>

**2** - Install [Macrodroid](https://play.google.com/store/apps/details?id=com.arlosoft.macrodroid) App on Smartwatch   
<details>
  <summary>Screenshot</summary>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/2.png?raw=true" alt="stacks"/>
</details>

**3** - Download Automate [Flows](https://github.com/musabcel/android_sp_sw_automation/tree/main/flows) and import (You can import directly by opening the flow file)
<details>
  <summary>Screenshot</summary>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/3.png?raw=true" alt="stacks"/>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/3_1.png?raw=true" alt="stacks"/>
</details>

**4** - Open Macrodroid App on Smartphone 

Add Macro → Add Triggers → Connectivity → Android Wear → Select Android Wear App

Add Actions → Application → Launch Shortcut → Flow Shortcut (Automate) → Select Flow
<details>
  <summary>Screenshot</summary>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/4_1.png?raw=true" alt="stacks"/>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/4_2.png?raw=true" alt="stacks"/>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/4_3.png?raw=true" alt="stacks"/>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/4_4.png?raw=true" alt="stacks"/>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/4_5.png?raw=true" alt="stacks"/>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/4_6.png?raw=true" alt="stacks"/>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/4_7.png?raw=true" alt="stacks"/>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/4_8.png?raw=true" alt="stacks"/>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/4_9.png?raw=true" alt="stacks"/>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/4_10.png?raw=true" alt="stacks"/>
</details>


**5** - Open Macrodroid App on Smartwatch and start the macro you added
<details>
  <summary>Screenshot</summary>
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/doc/5.gif?raw=true" alt="stacks"/>
</details>

# Flows
<details>
  <summary>Battery Statistics</summary>
  This flow will send your phone's battery information as a message dialog to your smart watch.
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/flows/Battery_Stats.flo.jpg?raw=true" alt="stacks"/>
</details>

<details>
  <summary>DND On/Off</summary>
  This flow is used to turn the do not disturb mode on or off on your phone.
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/flows/DND.flo.jpg?raw=true" alt="stacks"/>
</details>

<details>
  <summary>Ring Mode Change</summary>
  This flow is used to change the ring mode on your phone. It has sound on and vibrate mode.
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/flows/Ring_Mode.flo.jpg?raw=true"/>
</details>

<details>
  <summary>Watch_GPS</summary>
  This flow finds your phone's location and sends it as a notification to your smart watch.
  <img src="https://github.com/musabcel/android_sp_sw_automation/blob/main/flows/Watch_GPS.flo.jpg?raw=true"/>
</details>

