![openarm banner](/img/banner_openArm.png)

# What's OpenArm?
> An open-source robot arm_
> 
> [Github Repo](https://github.com/dmalawey/OpenArm) github.com/dmalawey/OpenArm
> 
> **PURPOSE: to design a robot arm using bio-inspiration for higher modularity and higher loads than leading commercial designs in 2023.**

## More Open Projects
More Open Source designs initiated by DM & SCUTTLE team:
* [SCUTTLE Nigeria](https://bit.ly/scuttleNigeria1)
* [Mechatronics Resources](https://bit.ly/openmechatronics)
* [OpenArm](https://bit.ly/openarm)
* [OpenJar](https://bit.ly/openjarproject_v1)
* [OpenBox](https://bit.ly/openboxproject)
* [OpenSpin](https://bit.ly/openspinproject)
* [OpenAir](https://bit.ly/openairproject)
* [OpenLab](https://bit.ly/openlabproject)

## Foreword

If an expert reviews this project, they will find numerous imperfections; potentially laughable ones.  A well-trained mechanical engineer would not _release_ such imperfections. But this project is not a release, just as every script posted in open software is not a final working script. We are pursuing a new paradigm, where open hardware ascends to match open software.  __In software, open development has surpassed privatized development.__ Developers discovered by publishing every step in realtime, we gain the world's contribution at every step, and 10,000 brilliant minds can outperform a well-paid team of 10 minds.  The only way to reach the new paradigm is to opensource the full development process, not only the end result.  So, we start the project with a goal and NOT with a build, and we trust experts to see the possibilities instead of the present status.  Then, we can incite the collaboration necessary to achieve the impossible.

There is no intention to reproduce a result that has existed before, so the result cannot be bought.  There is no deadline.  The prerequisite to completion is expertise, not funding or parts or tools.

 
# Design Log

## April 2024

April 4

AI has been available in search engines for several months now.  That's progress.  It means that all mechanical engineers just doubled their effectiveness in writing software (using the new tools).  It means designers in each discipline are twice as capable to gain understanding in a new discipline (with easier online explanations). And, it means hundreds of design teams around the world have realized they set their reach-targets too low in their planning stages in 2023. This project dream just became half as lofty as it was in 2023.

A discussion of sensors:  It will aid this project if we use new terminology.  In the definitions below, I added the word "feel."  In robotics, I've not found an equivalent term yet.  Consider an apple in your hand.  You can feel the apple is there. The outreached arm "feels" the apple, measured in the tension of the shoulder. To reproduce this in robots, traditional engineers place a torque sensor at the shoulder.  Next, rest your elbow on a desk.  It is no longer possible to use the shoulder sensor to sense the apple.  The human adjusts her attention to the wrist.  Chasing this capability in a robot, we then add a torque sensor at the wrist.  If you modify the situation again, we stack up more and more sensors and cost.  Next, double the weight of the apple.  The robot with lots of sensors still cannot measure if it has two apples or one large apple. As we develop solutions for a robot arm, "sense" can describe active collection of a datapoint while "feel" can describe the more general effort of deriving a useful parameter.  We can sense the weight of a clasped object or we can "feel" the weight by running a motion cycle and extracting a mass value from a delta in inertia.  We sense the size of an object with one eye and we feel it's distance by comparing info from our binocular vision.  We sense 

## December 2023

### Dec 29, 2023

Yesterday I had the pleasure of meeting Dr. David Surovik, employee 11 of Boston Dynamics' AI Institute.  He's actually a family member of a Texan friend of mine. This type of interaction (frequent, short meetings with deep experts) is critical, as robotics evolves so quickly.  Sometimes it evolves backwards, so we need to interact to avoid local minima.

My key "download" was basically the state of the art for robotics AI - there are some very ethical, good, hardworking people in the leading companies and the biggest question is regarding direction (what do we work on for the 5-year goal?) but everyone is doing their best.  I'm pleased to say there's nothing I learned that refutes the direction I'm establishing with OpenArm and SCUTTLE - that's great news.

### Dec 26, 2023

I've unburied my 2016 masters' thesis on Multidisciplinary Design Optimization of a Cubesat - an essential step in my understanding of how we will make robotics that evolve over time, and advance towards optimality.

You can find the video and a thoughtful description here in the youtube video:

[VIDEO LINK](https://youtu.be/XbSdwpLa4j4)

## June 2023

**Getting Started**

This deisgn will take a long time unless it becomes funded. Collaboration is encouraged.  Editing this repository is welcome.  Sharing comments & intellectual additions are encouraged by all.

Here are some early open design files.
| GrabCAD model of the first parts of the collar | [GrabCAD OpenArm](https://grabcad.com/library/openarm-2 ':class=button') |
| ---------------------------------------------- | ------------------------------------------------------------------------ |
| Photo album to share & collaborate | [Google Photo Album](https://photos.app.goo.gl/zSo8spTBcs2SwBfr6 ':class=button') |

**June 2023**

June 20

| Bearing loading with bb's, 4.5mm | Bearing on PVC, 60mm | Building Collars |
| -------------------------------- | -------------------- | ---------------- |
| ![Bearing 60mm on PVC](https://i.imgur.com/LxD7FG8.jpg) | ![bearing on pvc 60mm](https://i.imgur.com/3ticoLs.jpg) | ![img](https://i.imgur.com/GXAsp22.jpg) |

June 24

| early CAD model | gluing with PVC/ABS glue | Bearing tests 60mm & 89mm |
| --------------- | ------------------------ | ------------------------- |
| ![cad model](https://i.imgur.com/DGTnTfW.png) | ![PVC glue](https://i.imgur.com/uGdo5Hi.jpg) | ![5 bearings printed](https://i.imgur.com/ZZhuT2S.jpg)


June 25

| Steel balls, 9.5mm | Nylong Balls, 11.6mm | New CAD model - better parametrics |
| ------------------ | -------------------- | ---------------------------------- |
| ![cad model](https://i.imgur.com/2KZN6c2.jpg) | ![cad model](https://i.imgur.com/QbB7Jv3.png) | ![cad model](https://i.imgur.com/uohBkZG.png) |


The latest bearing uses these nylon balls from Amazon.com [link here](https://www.amazon.com/dp/B09WV4BZPC)

Here's a video testing out the bearing after printing:

<iframe width="640" height="360" src="https://www.youtube.com/embed/g5g48a-ZDeI" title="3D Printed Bearing with Nylon Balls" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

June 17: I am beginning modular design elements according with our "rules" and inviting the open community to collaborate.  Researchers, Makers, & Hackers Invited. 


| Bearing, affordable & printable   | Collar cross-section | Early conceptual sketch |
| --------------------------------- | -------------------- | ----------------------- |
| ![img1](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/42bde2079c49b20d65c9337484c22407/large.PNG) | ![img2](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/66d2971d7f5fd3bfa806faa31e257edc/large.png) | ![img3](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/97336228ee94392cfc37916c0e548c0c/large.jpg) |

## October 2023

October 15

| Prototype 2DOF | Prototype 2DOF |
| -------------- | -------------- |
| ![proto](https://i.imgur.com/8lMNrTj.jpg)) | ![proto2DOF](https://i.imgur.com/oqLZyIe.jpg) | 

This assembly moves nicely - now, deciding on the bearings and the motors will depend on the lifting task we wish to perform.  We can give more diameter to the members for greater rigidity, or make it light and fast.

October 20

| Quick Render| Motor Dimensions |
| ----------- | ---------------- |
| ![motor model](https://i.imgur.com/mhCejSM.png) | ![dimensions](https://i.imgur.com/8lfM9Xy.png) | 

Myself and collaborators went ahead and ordered a brushless motor to test integration.  This does not preclude us from using steppers or DC brushed motors later.   This month's challenge will be to look for the most elegant integration that leaves us with a parametric assembly.  Let's tie in these motors in such a way that changing motors will not pin down the design to one geometry.

**Unidirectional** By accident, we picked a controller (usually for RC planes) which spins only one direction.  At first it was a mistake - now I am on a thinking path about keeping it.  Your bicep only actuates in one direction.  Maybe that's a clever way to design a robot as well!  Later I can discuss how this could be an advantage.


# How You Can Help

| [Github Repo](https://github.com/dmalawey/OpenArm ':class=button') 
| [Website](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/dmalawey/OpenArm/main&sidebar=true#/?show-page-options=true ':class=button')
| 

## Why help?:

Most robot arms have missed the point of arms, and we should improve on this.

| Key Point | Our current robot arms:                                      | How God Designs arms:                                                    |
| --------- | ------------------------------------------------------------ | ------------------------------------------------------------------------ |
| 1         | One design = one product                                     | Make one design with many derivative instantiations                      |
| 2         | Energy is unlimited, and plugged in                          | Energy is portable, arms are portable                                    |
| 3         | Base receives high reaction forces.                          | Base sees no reaction forces OR reaction force contributes to the motion |
| 4         | Base must be rigidly secured.                                | Base may move.                                                           |
| 5         | Has rare materials like aircraft-aluminum                    | Has common materials like hydrocarbons.  :mortar_board: 3                |
| 6         | Components cost is imbalanced:<br>Muscles > Joints > members | Components cost is balanced:<br>muscles = joints = members               |
| 7         | Each joint receives independent control.                     | Joints are controlled together.                                          |


## Mechanical
* Building: I could use builders in parallel or in series - plenty of mistakes will need resolutions.  You may build an early revision that becomes overwritten but I guarantee you won't build anything without learning.  I will be building this project one module at a time.  Then we will need to resize it for various budgets or tasks.
* Design decisions: how much counterweight to add behind each joint?  where to place the counterweight?  Which parameters to build into the components vs build into the assemblies?  (does a long arm need just a longer member or a whole configuration of the assembly?  How can we input materials to keep the local center of gravity in the centerline of each joint?
* Modeling:  Lots of modeling to do. We can collaborate in solidworks or begin the equivalent designs in Fusion360 or other popular software.  We want this design to be as open and repeatable as possible so multiple formats are desired.
* Which nominal belts and pulleys are best suited, to leave space for increasing and decreasing the scale of the arm?  Are there kits to be bought in sets that have a high value, such as 3D printer actuators?
* Energy regeneration is important.  How can we select a motor type which balances high performance with useful regeneration?  This video from [Oren's Projects on youtube](https://youtu.be/HmUrjAJ5_jA?t=389) shows that energy regeneration for common brushless motors is negligible when measured in voltage.  But, we need to measure in energy.  Do we need to stay with bipolar DC motors in order for energy to return during backdriving?

## Electronics
* Our starting point is a 12v dc motor from the SCUTTLE robot.  It's a gearmotor - but which is the best choice for a base publication?  How will we route the wires through each member?  Should we make a variation of the bearings that have a slip ring?  can we prototype a bearing that has a slip ring functioning?
* Are there some off-the-shelf motor driver arrays from another application (like 3d printers, but for DC motors) that have a low-low cost?
* Is it possible to plan for both DC and Stepper motors simultaneously?  How big of an electrical mess is made if we backdrive the stepper motors?
* What standard OTS boards should the mechanical team make space for interior to the joints and members?
* Can the whole robot communicate with i2c?  Do we need somethign more robust like CAN-bus?
* We wish to recapture energy (even tiny amounts) when the small arm swings and backdrives the larger member.  how can we switch responsively between motor driving, motor breaking, and energy recap?
* Note: the purpose of energy recapture isn't to try to conserve all energy, it's to maintain in our models that the consumption will vary based on this - and gain understanding of the interactions so they can be modeled.

## Software
* which are the first models necessary to begin simulation?  what parameters do we need to output to help the simulation team operate effectively?  Are there some university or research courses currently operating on digital plans that we could offer this design to?  That's a win-win, then they could align their digital simulations with our design to give more meaning to their exercises.
* What measurements should be taken at what frequency?  Can we get away with no encoders at all?  Perhaps with a top-down camera the whole system could be tested under machine-vision learning.
* How should we assign variables and capture the performance metrics that come from software simulation?  What is the software control system, minimal-viable, that must be implemented to get a rough control scenario working on a real model?  Can we get away with something as cheap as an arduino?

## Documentation
* This project will be highly multidisciplinary in order to be successful.  To attract great talent, we need to make the physics & data very clear.  And to provide native design files for each element, as well as a clear BOM. 
* My recommendations
  1. BOM itemS - directly here in the readme.md, in a markdown table
  2. CAD data - grabCAD is preferred, using subdirectories for IMG, STEP, SOLIDWORKS
  3. Version numbers - add a version to each item and collection of items that may need repeating.  Use vX.XX please.
  4. Videos - Let's post on youTube and link here in markdown.  I can build a playlist as it grows.
  5. Discussion - best place to discuss this, TBD.  Feel free to comment on any of our postings to begin.

# References

| [Github Repo](https://github.com/dmalawey/OpenArm ':class=button') 
| [Website](https://qr.page/g/2wY5JrxcciD ':class=button')
|

## Definitions

* COTS: commercial-off-the-shelf.  Components with well-refined designs that can be purchased.
* Feel: For the robot, referring to a signal that can but isn't necessarily sensed and computed. It can be a digital datapoint from a sensor, a current or a voltage preceding a sensor, or a postprocessed datapoint derived from multiple inputs.
  
## Credits 👍

> _giving credit to prior works and contributions_
> 
> 1. Daniel Amuedo's design of the first parametric bearing, adapted for joints. His youtube channel is [Dangineering](https://www.youtube.com/@Dangineering).  I revised his [original solidworks model](https://www.printables.com/model/263264-200mm-bore-5mm-bore-cheap-ultra-thin-parametric-ba/filess) to get my bearing to print nicely, then further changed it to become part of a collar joint.  Thanks Daniel!
> 2. Oren's review on E-skateboard regenerative braking.  This data helps steer us to the right type of motor.  [Oren's Projects](https://youtu.be/HmUrjAJ5_jA?t=389)

## Sources 📖

> _Sources used in producing the project & documentation_
>
> 1. Markdown icons list [on github](https://gist.github.com/rxaviers/7360908#file-gistfile1-md)
> 2. Enhance image resolution online [cutout.pro](https://www.cutout.pro/photo-enhancer-sharpener-upscaler/upload)
> 3. Fonts from [Google Fonts](https://fonts.google.com/?query=robo)
> 4. Human Sketches from [Royal Collection Trust](https://www.rct.uk/collection/919013/the-muscles-of-the-shoulder-and-arm-recto-the-muscles-of-the-shoulder-and-arm-and)
> 5. Energy Regeneration trials from youtube [Oren's Projects](https://youtu.be/HmUrjAJ5_jA)
> 6. Icon Generator online [ICO-convert](https://icoconvert.com/)

## References 🎓

> _References in the discussion_
> These are referred above using icon and number such as :mortar_board: 1
>
> 1. GummiArm Project: A Replicable & Variable-stiffness Robot Arm [PDF Journal article](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8963345/pdf/fnbot-16-836772.pdf), [Youtube demo](https://youtu.be/ytCcpD84Jt0), and [Github Repository](https://github.com/mstoelen/GummiArm)
> 2. SCARA Arm example, Pybot, opensource, [Hackaday writeup](https://hackaday.io/project/175419-pybot-scara-robotic-arm-3d-printed-python)
> 3. What Bones are made of: NIH [webpage](https://www.niams.nih.gov/health-topics/what-bone#:~:text=Bone%20is%20made%20of%20protein,the%20bone%20can%20resist%20breaking.)
> 4. What Robot Arms are made of: Makeitfrom [Aluminums](https://www.makeitfrom.com/material-properties/6061-AlMg1SiCu-3.3214-H20-A96061-Aluminum)
> 5. Setup of UR Robot Arm: [universal robots video](https://video.universal-robots.com/ur-3-unboxing-video)
> 6. Fixtures for UR Robot: [Vention.io](https://vention.io/designs/ur5-robot-tending-bench-35492)
> 7. UR3e robot manual [PDF](https://s3-eu-west-1.amazonaws.com/ur-support-site/105370/99202_UR5_User_Manual_en_Global.pdf)
> 8. Chicken wing dissection [PDF guide](https://assist.asta.edu.au/sites/assist.asta.edu.au/files/SOP%20Performing%20a%20chicken%20wing%20dissection.pdf)
> 9. Kinova Robot Arm Manual [PDF](https://drive.google.com/file/d/1xQbkx1-v3SfAentKR9f3p3c2SVdViyQl/view)
> 10. Leonardo Da Vinci, 1452 [Repository by RCT](https://www.rct.uk/collection/919013/the-muscles-of-the-shoulder-and-arm-recto-the-muscles-of-the-shoulder-and-arm-and)