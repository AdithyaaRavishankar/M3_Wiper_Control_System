# M3_Wiper_Control_System
![wiper](https://user-images.githubusercontent.com/86227942/168279781-36069fb1-be4b-400a-a6ad-da109f23fe30.jpg)

Wipers are designed and manufactured to remove water from a windshield. Most automobiles feature two windshield wipers, as well as one on the back window and one on each headlight. The rubber blade, the wiper arm that holds the blade, a spring linkage, and portions of the wiper pivots are all visible from the exterior of the automobile. Under the wiper, there are up to six pieces called pressure points or claws, which are little arms. The claws spread the wiper's pressure along the blade's back. The wiper is the beam, and the claws are the suspension components, therefore this is a balancing beam with a suspension system. The claws keep the blade flexed against the windshield, distributing uniform pressure across the blade to clean the glass evenly. Large or strongly curved windshields benefit from more claws because they effectively disperse pressure.

# BADGES

* Build On Linux [![Build-Linux](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/buildonlinux.yml/badge.svg)](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/buildonlinux.yml)

* Codiga - Static Analysis
![Quality](https://api.codiga.io/project/33516/score/svg)

* Codiga
![Codiga Badge](https://api.codiga.io/project/33516/status/svg)

* Code Quality[![CodeQL](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/c-cpp.yml/badge.svg)](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/c-cpp.yml)

* Analysis [![Analysis](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/analysis.yml/badge.svg?branch=main)](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/analysis.yml)

* Build on Windows [![Build CI - Windows](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/buildonwindows.yml/badge.svg?branch=main)](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/buildonwindows.yml)

* Unit Test [![Unit Testing - Unity](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/unit_test.yml/badge.svg)](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/unit_test.yml)


* Gitinspector [![Contribution Check - Git Inspector](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/gitinspector.yml/badge.svg)](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/gitinspector.yml)

* Cppcheck [![cppcheck-action](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/cppcheck.yml/badge.svg?branch=main)](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/cppcheck.yml)

* valgrind [![Valgrind](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/valgrind.yml/badge.svg?branch=main)](https://github.com/AdithyaaRavishankar/M3_Wiper_Control_System/actions/workflows/valgrind.yml)
# INTRODUCTION
This Wiper Speed Control System is utilised in all sorts of automobiles, and its primary function is to remove rain air drops from the vehicle's front screen. Because driving a vehicle in the rain is quite difficult, we will use wipers to clear the front screen of the vehicle, which is a mirror, so that we may drive the vehicle even in the rain.

### WORKING OF THE SYSYTEM

* When the button is pressed ONCE, the car will be on ACC mode.

* When the button is pressed TWICE, the car will be on Ignition mode.

* When the button is pressed THREE times, wiper will turn on.

* When the button is pressed FOUR times, wiper will turn off.

# SWOT Analysis 

## Strength
* Visibility
* The wiper moves smoothly without getting stuck.
* Safe to use.

## Weakness 

* capital cost is high.
* It is not automatic.

## Threats 

* Once the when the board becomes faulty difficult to fix it.

# Requirements

## High level requirements

| ID | Discription | status |
| --- | --- | --- | 
| HR_01 |	Car is in Ingnition mode |	Implemented |
| HR_02 |	Car is in ACC mode |	Implemented |
| HR_03 |	Wiper turned on |	Implemented |
| HR_04 |	Wiper turned off |	Implemented |

## Low level requirements

| ID |	Discription |	status |
| --- | --- | --- | 
| LR_01 |	Button pressed ONCE for two seconds - ON LED RED |	Implemented |
| LR_02 |	Button pressed once again times - OFF LED RED |	Implemented |
| LR_03	| Button pressed two time - ON BLUE,GREEN,ORANGE |	Implemented |
| LR_04 |	Button pressed again for two seconds - OFF ORANGE,GREEN,BLUE |	Implemented | 
