---
tags:
  - teaching/cop5611
  - assignments
share_cop5611: "true"
site-folder: docs/Project
---
- [Overview](Semester%20Project.md#Overview)
- [Logistics](Semester%20Project.md#Logistics)
- [Sample project ideas](Semester%20Project.md#Sample%20project%20ideas)
- [Final submission requirements](Semester%20Project.md#Final%20submission%20requirements)
	- [Programming Projects](Semester%20Project.md#Final%20submission%20requirements)
- [Final presentation guidelines](Semester%20Project.md#Final%20presentation%20guidelines)
- [Grading](Semester%20Project.md#Grading)

## Overview

Pick something that is larger than a programming homework, yet achievable within the scope of a semester. It should be related to systems in some way, whether developing some systems code, creating or exploiting low-level interfaces, etc. Try getting your hands dirty system setup; don't just write an application in a high-level language. Any topics from the class are in scope, including, e.g., distributed systems, security, etc. If you have a personal project you are working on, that is okay as well, as long as you clearly delineate a portion to work on for the class, i.e., don't just take something you've already done. Try picking something you're curious about or interested in already. It may also be something academic, such as an in-depth study or literature review of a specific area of systems.

## Logistics

-   Propose the project first by the proposal due date. Write what you want to achieve, rougly the technical steps, and how to measure achievement.
-   Prepare a brief (no more than 10 minute) presentation/demo of your project by the project due date.
-   Submit the project according to the syllabus.
-   Work on your own. Group projects possible in compelling cases.  Please request instructor approval.
-   Follow the rules about academic integrity.

## Sample project ideas

These are only suggestions and you may come up with your own.

-   kernel from scratch
-   write a shell
-   write a distributed application using low-level primitives
-   design an IoT device using a raspberry pi, e.g., automatic blinds that close when it detects sunlight
-   implement a memory allocator from scratch
-   use the nds for something (network interop, etc)
-   literature review on a particular topic (paper and presentation)
-   make a new linux kernel module
-   modify the linux kernel
-   do some kernel tracing
-   run a kernel fuzzer
-   explore library os
-   exposing hardware to higher-level software, e.g., usb thermometer, you want to write a OS driver, or raw mode I/O C application
-   adding a new syscall
-   [https://github.com/RossMeikleham/UEFIBoy](https://github.com/RossMeikleham/UEFIBoy)
-   bootloaders (EFI)
-   virtual machines
-   hack on low-level systems for mobile devices, handheld game consoles, etc
-   write simulators for some aspect of the kernel, scheduling, virtual memory, etc
-   novel implementation of FUSE (Filesystem in USEr space)

## Final submission requirements
### Programming Projects
You will turn in a 3-5 page write-up on your project following the following outline:
- Introduction
	- Briefly describe your project's domain area and what motivated your interest.
	- What are you trying to accomplish and/or learn?
	- Describe specific goals for the project.
- Methodology
	- How are you going to accomplish your goals?  Describe the technical aspects of the project. i.e.:
		- Hardware
		- Software libraries/APIs.
		- Programming languages/platforms
		- Algorithms implemented
		- Describe how these aspects relate to one another, i.e.: system architecture/design
- Results
	- Which goals were achieved and to what extent?
		- Give all appropriate quantitative results (i.e., benchmark results)
		- Don't be afraid to talk about failed goals because...
	- Learning is important.  What did you learn?
		- Think about all aspects of the project, not just the technical.
			- Time management/planning
			- Learning curve
			- Specific technical obstacles
- Conclusion
	- Summarize your findings 
	- Describe any special insights or personal notes about the topic and/or process



## Final presentation guidelines

- Final presentation slides should follow the outline for the write-up.
- Keep the total length of the presentation to around 10 minutes.  As a general guideline, allow 1 minute per slide of presentation.  
- Programming projects require a demo.  Live demos are preferred, but pre-recorded demos can be accepted if there's no way to present live due to access to hardware or software.
## Grading
- You will be evaluated based on what you proposed, with an awareness that plans don't always work out
- You won't be penalized if you have a good story around any changes in goals or results
- Detailed Rubric is TBD