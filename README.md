# SFT Mk 4 - FreeCAD Project
This is a [FreeCAD](https://freecad.org/) project to model the [Switched Flux Transmission](https://tomboy-pink.co.uk/SFT/) device invented by Prajna Pranab.

![luxcorerender1](https://github.com/prajna-pranab/SFT/assets/4018272/507b2ab9-f08d-45ae-ac46-6c79fb8a82e0)

*SFT-Mk4 render image (using Luxcore)*

To work with the complete assembly you will need to install the following  addons via the FreeCAD Addons Manager: Assembly 4 Workbench; Fasteners Workbench; for rendering, the Render Workbench.

The model is organised as an Assembly 4 project and the assembly is contained in [asm_SFT-Mk4.FCStd](./asm_SFT-Mk4.FCStd), so open that file in FreeCAD and it will open all the other parts. Once you've opened the project file, switch to the Assembly 4 Workbench and look near the top of the tree for the Variables object. In the Variables object properties you will find a Variable called _Rotor Angle_. The moveable parts positions are all calculated from the rotor axle's angle (specified in _Rotor Angle_) and you can adjust the state of the model by changing the value of _Rotor Angle_. You can also click the Animate Assembly button and select _Rotor Angle_ as the variable to control.

For full details on what this SFT device is visit my [website](https://tomboy-pink.co.uk/SFT/)

There's plenty more to do. Some things that need checking in this model: Fitting and clearence of the holes that receive shafts and axles; I've only been working with FreeCAD for a month, so a level of inexpertise may be obvious to some skilled in the art and science of it; There is still work to do on the render setup (I'm still learning about that); I've never 3D printed anything and those who have may look at this design in horror at the lack of support or extravagant use of filament and probably other stuff I have no idea about, so I hope to find some pointers on that at our local(ish) FabLab and the design may dramatically change when I've been there. Feel free to [join the discussion][Discussion] or raise an issue if you see something that could be better.

## Update

I went to visit my local [FabLab](https://www.fablabs.io/labs/fablabaldeiasdoxisto) to discuss the project. The guy I spoke to seems to think (from a quick look at the rendered image) that the model will be easy to print but there is a week-long event at the lab this week, so it will probably be next week before there is an opportunity to sit down with them.

26 May 24 - I returned to FabLab and was given a run-through of Prusa Slicer, installed and configured it on my laptop and then laid out the printable parts in Prusa. I also emailed https://www.coleherne.co.uk/, who specialise in electrical steel laminations, to ask for advice on the suitability of electrical steel for the Tabs/Fingers. They claim to offer such expertise and have a department for prototyping laminations using a laser cutter. Hopefully they will not be put off responding because it "looks like a free energy device."

2 June 24 - Didn't hear back from Coleherne Ltd re laminations so have emailed three other lamination companies. Everything is laid out for printing and we're off to FabLab tomorrow to do that. I have started a new branch "capnut" because it was not easy to source inserts and grubscrews easily locally so I have refactored things to use captive nuts rather than inserts. That involved resizing various hubs and modifying/moving other parts to accommodate the nuts.

## Acknowledgements

A big shout out to Robert Murray-Smith, whose video about the Wesley Gary magnetic motor inspired this device. The wonderful renders could not have been done without the dedication and prompt updating of the FreeCAD Render Workbench by @howetuft to address issues I was having.

## Feedback and involvement

I've set up `Discussions` as a space to discuss this project.

Please be friendly and constructive. 

Here's the [Discussion][Discussion].

To follow any activity in the repository, switch on the `Watch` functionality. If you find the project interesting, please star the repository. Starring a repository also shows appreciation to the repository maintainer for their work. You can star repositories and topics to keep track of projects you find interesting and discover related content in your news feed. Check out [Saving repositories with stars](https://docs.github.com/en/get-started/exploring-projects-on-github/saving-repositories-with-stars) to get more.

[Discussion]: https://github.com/prajna-pranab/SFT/discussions
