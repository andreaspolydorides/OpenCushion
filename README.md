# OpenCushion
**NOTE:** This project is not yet ready for release, but this alpha version is available for testing and feedback. For pending tasks before revision 1 is released, check out the To-Do section below.

![OpenCushion_Logo](/assets/images/opencushion-logo.png)

## What is OpenCushion?
OpenCushion is an open-source project aiming to improve the accessibility of personalized wheelchair cushions. Its design focuses on financial and geographical accessibility. It aims to be affordable and possible to make with any standard consumer-level 3D printer. To personalize the cushion to each user’s individual pressure needs, this design customizes the density of a 3D printed lattice so that areas of high pressure exhibit low density and vice versa, with the aim of distributing pressure evenly.

## Why does it exist?
The project was born from user research that indicated contrasting levels of comfort between manual and power wheelchair users, with the former group being at a significant disadvantage. Personalized cushions are expensive, as individual molds see the price rise substantially, and with wheelchair users already modifying their wheelchairs to better suit their needs, OpenCushion offers a tool to create a cushion which they can test and consult their occupational therapist (OT) about.

## Who is it for?
This is a DIY project, so it is inherently more complex than ordering a cushion online or having one made by a service provider. You can either make one yourself with a 3D printer you have access to (your own, a friend’s or a local makerspace’s) or talk to a 3D printing service provider on a platform like Etsy to get one done. If you do not already have access to a 3D printer, we advise you not to buy one for this project specifically, as the cost might be near that of a market cushion. This project assumes some familiarity with 3D printers and basic troubleshooting abilities. No knowledge of 3D CAD or programming is needed.

## What do you need?
All you need is a 3D printer and TPU/TPE filament, we use 40D and 83A shore hardness ones (e.g. [eSUN TPE 83A 1KG](https://www.amazon.co.uk/dp/B07VLS8GWD)). A computer capable of running slicer software (not very demanding) is also needed – check your public library if you don’t have one.
Wheelchair cushions tend to be wider and deeper than standard size 3D printers – you don’t need a large printer, two of three methods here allow you to print smaller pieces to then join together, and soon all three will.

## Which method to use?
Depending on your exact circumstances, you might find that a different method works best for you. Do note that as of now there is no inherently better method, they’re multiple ways of achieving the same effect that will appeal to different people. For how each method works, look at their individual sections.

### Method 1: GCODE Generation
Use this method if you have access to a pressure map – talk to your OT about getting the data from it (should be a simple .csv or Excel file). Currently, this method does not support printing a cushion in smaller pieces, so only use this if the size of your printer is larger than that of your desired cushion’s.

### Method 2: Post-processing
This method should be used if you have access to a pressure map – talk to your OT about getting the data from it (should be a simple .csv or Excel file). This method allows printing a cushion in smaller pieces so you can use any size printer you want. Note that if you use a very small printer the number of cushion pieces can grow and the chances of accidentally printing the wrong part twice increase!

### Method 3: SVG Modifier
This method was developed to counter the lack of access to a pressure map, instead mimicking one through some manual work in the slicer. Use this if you definitely cannot access a pressure map, as the level of personalization you can get here is limited. With this method, you can print a cushion in smaller pieces so the same advice as above stands.


## Planned To-Dos
- [ ] Finish the How-Tos on this Github page
- [ ] Set up a website for generation tools, a library of SVG sets and help guides
- [ ] Set up a Discord server for community support and discussion
- [ ] Create gyroid lattice for GCODE Generation method
- [ ] Run material testing on lattices to inform suggestions
