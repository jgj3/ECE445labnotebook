# ECE445 lab notebook

## WEEK 1 2/9
1. completed the CAD sodering assignment
2. had first meeting with TA discussing project scope and how exactly the sensors work
3. researched MAX 86141 and SFH 7050 to see how the chips function 
4. wrote up the proposal
## WEEK 2 2/16
1. started a course in nRF SDK connect online and learning how to code via nordic semiconductor
2. wrote up the team contract
3. preparing both pcbs for reviews working on the schematic
4. preparing for breadboard demo with having to find a way to show the circuit
## WEEK 3 2/23
1. wrote the design document for the whole week
2. finished up schematics with teammates and got it checked by TA
3. started editing board layout and assigning footprints to all chips
4. first round of ecg completed and ordered
5. Designed breakout boards since PPG will not arrive
## WEEK 4 3/2
1. prepare for design review iron out any other details
2. test ecg sensor to prepare for breadboard demo
3. breakout boards didnt arrive in time for the breadboard demo so luckily we were able to pivot to our ecg sensor that arrived
4. we tested our ecg using a waveform generator to show the wave connected via matlab
5. ! <img width="682" height="839" alt="connect" src="https://github.com/user-attachments/assets/efb3855c-cdef-4f30-931e-2630643d85d1" />
## WEEK 5 3/9
1. complete teamwork evaluation
2. began to find alternative connections methods using vsc
3. ordered ppg sensor redesigned board because we wanted to connect the two ppg sensors as one to use only one nRF chip for both of the ppg sensors
4. continuing to learn software
## WEEK 6 3/16
1. spring break so finished my course in the nRF SDK connect
2. double checked the schematics for the ecg
3. changed some minor things in the ppg sensor design with long squiggle lines holding the photdioode resistors next to our earlobes and this way the PCB is a little more stretchable
## WEEK 7 3/23
1. prepare for progress demo with ppg sensor testing it using a light to show the waves on the phone app
2. continuing testing on daily basis for trying to implemenet full software to work with fingers
## WEEK 8 3/30
1. when using fingers too much noise is being shown on the plot and we are in the process of trying to identift the root cause of the issue
2. performing root cause analysis to determine what is causing all the other noise
3. connect ppg via phone app for the progress demo
## WEEK 9 4/6
1. progress demo done showed PPG working with flashlight rather than fingers to show peaks of the wave
2. our testing has revealed that the long squiggle lines and putting the MAX chips so far away from the PDRs was a possible cause of the large noise readings
3. redesigned a new board unfortunately deadline passed but removed the long squiggling lines
4. trying to fix software and added filters which made the light very clear and identifable but fingers were showing no values
5. the main issue we have identified from our testing seems to be the potential difference supplied to the PDR is incorrect
## WEEK 10 4/13
1. encountering major noise from the ppg sensor on all pulse readings
2. tried testing outside the lab because thought the noise was from the sockets in the room but no better
3. hoping newly designed PCB arrives quickly working with old iteration to make sure the software has no issues
4. had to fix entire config file since register values were incorrect for all of them
## WEEK 11 4/20
1. preparing for mock presentation with doing slideshow
2. had mock demo during the week with shiyuan showed him the ecg sensor
3. new ppg board delievered and sodering complete conducting testing over the weekend
4. PPG does not work lights from PDR not showing up out of ideas
5. ECG sensor working perfectly trying to encapsulate it
## WEEK 12 4/27
1. had final demo hopefully went well
2. preparing a second mock presentation to show our TA on thursday
3. tried till monday last minute to try and fix the ppg but it didnt work
4. we encapsulated the entire ecg sensor with foam and connected pin up electrodes
5. our presentation is ready for next weeks presentation
6. doing final paper
7. preparing lab notebooks
