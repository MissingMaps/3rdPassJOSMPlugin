# 3rdPass validation Missing Maps Plugin
JOSM plugin with set of quality checkers useful for 3rdpass validation on HOT Tasking Manager projects. This plugin was developed with assistance from AI chatbot Claude (Anthropic).

**How to add into JOSM:**
![image](https://raw.githubusercontent.com/MissingMaps/3rdPassJOSMPlugin/refs/heads/main/resources/images/plugin_installation.gif)

- Open JOSM and go to preferences {F12}
- Toggle on Expert Mode in bottom left corner
- Go to Plugins 
  - Configure sites... -> Add -> https://raw.githubusercontent.com/MissingMaps/3rdPassJOSMPlugin/main/plugin.txt -> Okay
  - Download list
  - New plugin should appear called 3rdPassMM -> install as usual (check the box hit Okay on the bottom)

This way you will get automatic updates if there will be a new version of the plugin. This is an early version of the plugin, once I am comfortable with it I will publish it on the JOSM plugins library so this step won't be necessary anymore.

What does it detect
- Residential areas without highway going over or into them - might be useful for project creation
- Residential areas with more then 1 place node inside them
- Change in sandwich road classification. For example path - unclassified - path it will select the unclassified part of the highway
- For better understanding you can download the "3rdPassMM_plugin_showcase.osm" file to see what it is supposed to detect

This plugin was created because java is able to run more advanced analysis then paint style or validation plugin rules which are both written in mapcss so their usecase is more limited.

Please for any issues, bugs but also feature ideas reach out to [Patrik_B](https://www.openstreetmap.org/user/Patrik_B) over HOT Slack or email at patrik.brigant@prague.msf.org
