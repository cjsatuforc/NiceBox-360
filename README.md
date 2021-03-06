# NiceBox-360
NiceBox-360 is a script for Fusion 360 for designing laser-cut and mill-cut boxes.

### Inputs 
Input for the script is a array of parameters. Parameters describes size of the box, material and tool of production. More information and examples you can find it below. 

### Outputs
Outputs of the script are a 3D model of the box and 6 sketches. Each sketch is a blueprint of the wall of the box, which you can save as .dxf and use for production.

# How it's work ?
When you launch script box will appear with default parameters.

![Alt text](/resources/Images/Origin.jpg?raw=true "Original")

**Wall** parameter changes wall thickness. 
_This parameter is a physical thickness of material which you will use for production. In our case 3mm plywood is very popular choice._

![Alt text](/resources/Images/Wall.jpg?raw=true "Wall")

**Height** parameter changes height of the box.

![Alt text](/resources/Images/Height.jpg?raw=true "Height")

**Width** parameter changes width of the box.

![Alt text](/resources/Images/Width.jpg?raw=true "Width")

**Depth** parameter changes depth of the box.

![Alt text](/resources/Images/Depth.jpg?raw=true "Depth")

**Kerf Laser Cut** parameter is defined as the width of material that is removed by a cutting process.

![Alt text](/resources/Images/Kerf.jpg?raw=true "Shift")

**Mill diameter** diameter of mill tool.
_Keep it at 0, if you don't use mill router for the manufactoring._

![Alt text](/resources/Images/Mill.jpg?raw=true "Shift")

**Shift** parameter is a value how deep top, bottom, back and front are placed relatively to edge of the box.
_Good example here is 0mm._

![Alt text](/resources/Images/Shift.jpg?raw=true "Shift")

**Tooth proportion** the ratio of the length of the tooth to the length of a side.

![Alt text](/resources/Images/Tooth.jpg?raw=true "Shift")

# Installing
Click on **Clone or Download button**, then **Download ZIP**. Unzip that files in script folder on your computer:

For Windows:    
%appdata%\Autodesk\Autodesk Fusion 360\API\Scripts

For Mac:    
~/Library/Application Support/Autodesk/Autodesk Fusion 360/API/Scripts

# Timeline of out project
| Date          | Event                                                                                    | DeadLine    |
| ------------- |:-----------------------------------------------------------------------------------------| -----------:|
| 29.03.2017    | Project initialization: <br> Team creation, task definition, participation in the hackathon "3D hackathon" <br> - https://adncis.timepad.ru/event/453896/                                                                    | 31.03.2017  |
| 31.03.2017    | Our team: <br> https://github.com/azamtau  <br> https://github.com/copypastestd  <br> https://github.com/PhilippNox <br> Project **NiceBox-360** <br> Our team took 2nd place on the hakaton in the nomination **_Fusion 360_**| 02.04.2017  |
| 25.04.2017    | GitHub publication                                                                       | 10.05.2017  |
| 26.04.2017    | Preparation of the grant application                                                     | 09.05.2017  |

# ToDo List
| Feature                                                                   | Comment                      |   Status    |
| ------------------------------------------------------------------------- |:-----------------------------| -----------:|
| **Renaming:** Create bodies in separate components with appropriate names | **_-BoxName_** parameter     | 90%  Done   |
| **Fix combine** Already replaced by Extrude from sketches                 | Need code refactoring        | 100% Done   |
| **Parameters** Add all inputs to user parameters                          | No code interaction          | 25%  Done   |
| **Milling:**  Add special holes for mill tool                             | Need to add validations      | 60%  Done   |
| **Patterns:**  Add patterns saving in file                                | Need to add custom folder    | 90%  Done   |
| **Viewer:**  Add View API for demonstration                               | Check Autodesk updates       | 25%  Done   |
| **instructables.com:**  Add instruction to the website                    | Need Viewer                  | 25%  Done   |
| **Multiple spikes:**  Add the ability to change the number of spikes      |                              | 10%  Done   |



# FAQ
**When you script will be available on Fusion 360 Store?**<br>
In our plans to publish NiceBox during May-June 2017.

**How much will your script cost?**<br>
Our project is opensource and free to use.

# License

    Licensed under Attribution-ShareAlike 4.0 International (CC BY-SA 4.0). 

[![License: CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/80x15.png)](http://creativecommons.org/licenses/by-sa/4.0/)
