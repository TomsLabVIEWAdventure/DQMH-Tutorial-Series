# DQMH-Vending-Machine
A DQMH approach to a simulated vending machine. This commit uses 5 DQMH modules (Model, Keypad, Stock, Display and Money) to demonstrate a reusable and saleable approach.


The Delacor Queued Message Handler (DQMH)
The following is copied from https://delacor.com/products/dqmh/
*********************
The DQMH® is a free product based on the National Instruments Queued Message Handler Project Template (NI QMH). The DQMH expands on the NI QMH by providing safe, event-based message handling and scripting tools to make development easy, encourage same style between different developers in the same project and improve efficiency. The DQMH is ideal for applications where multiple modules must run in parallel, possibly at different rates, while communicating with each other. The DQMH can also be used for applications that have a single module, where the developer would benefit from having a Tester with the capability of eavesdropping on the different DQMH events and messages. The built-in productivity tools make it very easy to add modules to existing projects without having to start from the project template.  In addition, there are tools to add and remove events by selecting the desired action from the Tools>Delacor>DQMH menu. The DQMH easily integrates with TestStand since all development and troubleshooting can take place under LabVIEW, while calling the public API VIs as individual steps in the Teststand sequence.  The tester can eavesdrop during the execution of the TestStand sequence. This is especially useful when the LabVIEW code is written during the research and development or prototyping phase, because the same code can be easily called by TestStand in production or manufacturing sequences without any changes. The DQMH uses LVOOP for some internal functions, but developers need not be familiar with LVOOP to use or understand this architecture.

DQMH is available for LabVIEW 2014 or later.
*********************

*********************
It uses the transparency toolkit from SSDC (Steve Watts)
http://www.ssdc.co.uk/downloads.php
https://forums.ni.com/t5/LabVIEW-News/Sick-of-Rectangles-Make-Your-Splash-Screen-More-Interesting/ba-p/3488696?profile.language=en
*********************

*********************
It uses the drop-in VI to click and drag the panel. The original source code is available here:
https://forums.ni.com/t5/Example-Programs/Position-Front-Panel-with-Mouse-Drag-Using-LabVIEW/ta-p/3524721?profile.language=en
*********************
