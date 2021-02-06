# Title: Immediate Threat Detection
### Project creator: Daniel Shifman
## Summary
The project will recognize weapons (handguns and knives at a minimum.)
The detected weapons will be highlighted based on category.
The major vision problem to handle is object detection.
## Background
The goal will be to detect, identify, and draw attention to weapons in frame
of an arbitrary camera. The camera may be any type of camera so long as the
local device is made aware of it (including IP cameras.) This can be helpful
for security purposes in that security personnel (police, airport security, etc) may
scan for weapons while not being physically present (for safety reasons.) This can allow
for numerous security applications such as threat assessment in hostage situations,
general law enforcement training, or airport security. For instance, in the case of law
enforcement, a real-time weapon detection may assist personnel in learning to
recognize locations in which to look for weapons.
## The Challenge
This project was chosen in part for the low likelihood of finding any publicly-available
weapon detection software (be it precompiled, source, or libraries.) In addition to this, there are also the challenges of recognizing the shapes of the many various weapons (which is why the minimum goal is only handgun and knife recognition) and tracking held weapons as they move. Another challenge to face is testing during development. As the project creator does not own any firearms, testing handgun (and any other firearm) recognition may prove to be an inconvenient obstacle. A possibility around this is to test recognition of firearms in a virtually rendered environment passed in as a virtual camera.

The learning objective of this particular project is to learn how to detect objects, track moving objects, and recognize objects. A simple planned flowchart is shown below in figure one, and a visual depiction of a final result use case is shown below in figure 2.

![](https://i.ibb.co/BKpVFxv/Flowchart.png)

*Figure 1: Flowchart*




![](https://i.ibb.co/hcbQd2b/useCase.png)
*Figure 2: Use Case*

### Goals and Deliverables
The primary planned goal of the project is to detect, identify, track, and highlight any in-frame handguns and knives. Provided time allows, the project will also detect, identify, track, and highlight various other weapons as well as people moving towards a weapon.

In order to recognize a successful outcome, test cases will be created with a recorded quantity of weapons in recorded positions. The weapons detected in each test will be recorded and compared to the actual quantities and positions in frame. As aforementioned, for the purposes of testing firearm recognition, a virtual environment may be used to achieve equivalent conditions.

It is believed that there is adequate time allotted to for the project to be completed to the defined minimum requirements.

## Schedule

| Week | Dates | Goal |
|-------|------|------|
| 1 | Feb 7- Feb 13 | Setup basic program to read feed from arbitrary input and output unaltered feed, acquire or create weapon datasets |
| 2 | Feb 14 - Feb 20 | Begin knife recognition and identification|
| 3 | Feb 21 - Feb 27 | Begin handgun recognition and identification|
| 4| Feb 28 - Mar 6 | Have basic weapon recognition and identification completed |
| 5 | Mar 7 - Mar 13 |  Begin object tracking|
| 6 | Mar 14 - Mar 20 | Complete object tracking, review speed and efficiency|
| 7 | Mar 21 - Mar 27 | Run extensive testing |
| 8 | Mar 28 - Apr 3 | Begin additional weapon recognition and identification |
| 9 | Apr 4 - Apr 10 | Run extensive testing |
| 10 | Apr 11 - Apr 14 | Final testing and bug fixes |
