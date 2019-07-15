# value-uncertainty
Value uncertainty task

This file provides brief descriptions of schedules and only critical variables within schedules. Contact astolyarova@psych.ucla.edu with questions about schedules and all other variables. Please also email astolyarova@psych.ucla.edu for help with changing/modifying these schedules or to request additional versions of existing tasks (e.g., small changes have been made throughout the years for efficiency and improvement, if interested in a particular version of the task, please email and I’ll provide that version if it had been used by us previously).

Pre-training:
Phase1: Habituation phase, delivers 5 pellets and tracks screen touches.
Phase2: Initial touch to center, rats learn to nosepoke the white square stimulus at the center of the screen to receive rewards.
Phase3: Immediate reward. After initiation, one of the Training_Images is presented on one of the response sides (left or right). Rats need to nose-poke the presented training image to receive reward. 
Phase4: Stable equivalent delay. This stage is identical to Phase3, except a 5 second stable delay is introduced between the training image touch and reward delivery. 

Main task: 
Each trial begins with stimulus (bright white square) presentation in the central compartment of the touchscreen. Rats are given 40 seconds to initiate a trial. If 40 seconds pass without a response, the trial is scored as an “initiation omission”. Following a nose-poke to the central compartment, the central cue disappears and two choice stimuli are presented concurrently in each of the side compartments of the touchscreen allowing an animal a free choice between two reward options. Stimulus-response side assignments are held constant for each animal to facilitate learning. Each response option is associated with the delivery of one sugar pellet after a delay interval. The delays associated with each option are pooled from distributions that are identical in mean value, but different in variability (LV vs HV; ~N(µ, σ): μ=10, σHV=4s σLV=1). An animal is given 40 seconds to make a choice; failure to select an option within this time interval results in the trial being scored as “choice omission” and beginning of an ITI. 
Reward upshifts decrease the mean of delay to 5 seconds with variance kept constant and downshifts increase the mean delay to 20 seconds on each option independently. 


Making changes to variables:
Novel stimuli are presented during the main task (training stimuli that appeared during training are no longer used). Presented stimuli can be modified by linking new stimuli to the Images list.
To modify delay to rewards, change the values in delay_to_reward lists (there is a separate list for HV delays and a separate list for LV delays). For example, values of delay to reward can be generated in MatLab according to the desired distribution and then copied into the delay_to_reward lists through insert->add values->specify with delimiter.
To change the amount of time that is given to rats to indicate their choice after response stimulus presentation, choice_time variable can be modified. 
To change the amount of time that is given to rats to initiate a trial after initiation stimulus presentation, initiation_time variable can be modified. 
To change the duration of the inter-trial interval, ITI variable can be modified. 


Please contact us (astolyarova@psych.ucla.edu) with questions, or requests for additional changes, modifications and versions.
