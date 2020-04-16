
# Seira-5 Instruction Manual

The Instruction Manual of Seira-5 by Bullseye/ Manufacturing Seira-5 for Process Manufacturing User's Guide @ Bullseye

This is an instruction manual of a "weight-fill & auto dispensing precision powder equipment" and its inner "manual weigh fill helper software" invented by Shenzhen Bullseye Dosing Technology Co., Ltd. 

# Weighing & Dispensing 

Weighing and Dispensing the right quantity of material prior to the manufacturing process is a key activity in LED Packaging and other process industries. The process is critical when operating with LED phosphor powders which exhibit the phenomenon of luminescence in making mixture of A/B Glues and the powders. Decimal errors in the "glue and powder mixture" calculation would not be able to tune phosphors for better white light. Advances in the weighing boost the efficiency and appeal better light in LED bulbs. Companies pre weigh materials to aim for better color of LED lights and to assure rapid delivery at the critical stages of the LED packaging process.

Seira-5 lets you produce the mixture in several modes of operation with full label printing capabilities. Functionality supported includes:

- Weighing and Dispensing Modes
- METTLER TOLEDO Weigh Module (accurate to 0.0001)
- Tolerances
- Operating Alarm
- Label Printing 
- Equipment Maintenance
  
  
 ### This Manual covers the following topics:
  
 - [Equipment startup and shutdown](#equipment-startup-and-shutdown)
 - [Auto/Manual Mode](#auto/manual-mode)
 - [Materials Feeding](#materials-feeding)
 - Generate the formula
 - Batching operation
 - How to clean phosphor feeder
 - Phosphors parameter adjustment
 - How to clean glue feeder
 - Glue parameter adjustment 
 - Viewing the dispensed material activity details
 - Alarm prompt and how to stop the prompt
 - Equipment maintenance
 - How to calibrate the METTLER TOLEDO Weigh Module
 - Video demonstration
 - Support
 
 
 ## Equipment Startup and Shutdown

### How to Startup

1. Connect the Compressing air and GND of the equipment, and connect the power of the equipment.

2. Turn the emergency switch on the left side of the chassis 90 degrees clockwise to turn on the main power of the equipment.

3. Turn the emergency button on the front of the case clockwise, the button will pop up automatically and connect the control power of the equipment.

4. Push the hand valve inward to turn on the air pressure.

5. Press the monitor power button to turn on the monitor.

6. The computer of the equipment automatically starts to enter the system.

7. Double click to run the software and log in the account.

8. Click the red **MANUAL** in the **Operation Monitoring** to make it green **Automation**, and then click **Reset** to wait for the red light above the equipment to go out.

### How to Shutdown

1. Click the **X** button in the navigation bar at the top right to exit the software.

2. Turn off the power of the host from the start, and press the power button of the monitor to turn off the power.

3. Push the valve outward to close the air pressure.

4. Press the emergency stop button on the front of the chassis to turn off the power of the equipment.

5. Turn the emergency stop switch on the left side of the chassis 90 degrees anticlockwise to turn off the main power supply of the equipment. When there is a powder, the power-off time should not exceed 30 minutes.

 ## Auto/Manual Mode
 
1. Enter the technician **Debugging Servo** setting,

2. Switch to the manual mode, click the servo setting interface, and click **Auto Enable** to make the green light behind it turn red.

3. Click to **Manual Enable**, then click to **Return to The Origin**, and wait for the completion of returning to the origin.

4. Change from manual mode to automation mode, click the corresponding servo setting interface, and then click **Auto Enable** to make the red light behind it turn green,

5. Then click **Return to Origin** and wait for the completion of the return to origin.

 ## Materials Feeding

### Scanning Powdering

1. Log in the account to enter the **Operation Monitoring**.

2. When the equipment is in standby mode, click the **Feeding** button to enter the Feeding interface.

3. Click the input on the right side of the barcode scanning area, and then to scan the barcode on the powder bottle. The powder loading funnel of the scanned barcode will automatically move to the powder Feeding port, and the powder Feeding light will be green, with an audible prompt.

4. Open the glass window, remove the inner cover and add the powder, then close the glass window with the inner cover.

5. Click the **Feeding Completion**, pop up the powder Feeding weight box, and enter the weight in the powder Feeding weight column.

6. Click **OK**, the powder funnel will automatically move back to the origin, and the powder Feeding is completed.

7. If the powder in the powder funnel is very small before Feeding powder, and it has exposed the discharge port of the powder funnel, it is necessary to discharge the powder 2 to 10 times, each time the weight is 2g to 5g.

### Manual Powdering


1. In the case of no scanning gun, click the **Moving Position** behind the powder to be added, the powder loading funnel will automatically move to the powder Feeding port, the powder Feeding position light will be green, with an audible prompt.

2. Open the glass window, remove the inner cover and add the powder, then close the glass window with the inner cover. Enter the weight of the remaining powder in the powder funnel in the input box of the weight column corresponding to the added material. Note that the input value cannot be more than that in the actual powder funnel, and it can be slightly less.

3. Open the glass window, remove the inner cover and add the powder of the scanned barcode, then close the glass window with the inner cover.

4. Click **Add Completion** to finish, pop up the add powder weight box, and enter the add powder weight in the added powder weight column.

5. Click **OK**, the powder funnel will automatically move back to the origin, and the powder Feeding is completed.

6. If the powder in the powder funnel is small before Feeding powder, and it has exposed the discharge port of the powder funnel, it is necessary to discharge the powder 2 to 10 times, each time the weight is 2G to 5g.


### Scanning Glue

1. When the equipment is in standby mode, click the **Feeding** button in the interface to enter the charging interface.

2. Click the input field on the right side of the barcode scanning area, and then use the scanning gun to scan the barcode on the plastic bottle. The air pressure in the corresponding glue tank will be discharged, and the air pressure light of the glue in the interface will be red.

3. After venting, open the sealing cover and pour it in A/B glue.

4. Close the sealing cover, click the **Feeding completion**, pop up the glue Feeding weight box, and enter the glue Feeding weight in the glue Feeding weight column.

5. Click **OK**, the air pressure will be automatically added into the tank, and the filling is completed.


### Manual Glue
1. If there is no scanning gun, open the **Material Valve** behind the glue, the air pressure in the corresponding glue tank will be discharged, and the air pressure light of the glue in the interface will be red.

2. After venting, open the sealing cover and pour in A/B glue,

3. Close the sealing cover, click the **Feeding completion**, pop up the glue Feeding weight box, and enter the glue Feeding weight in the glue Feeding weight column.

4. Click **OK**, the air pressure will be automatically added into the tank, and the filling is completed



## Formulas

1. Click **Recipe Management-Management** to enter the recipe management interface, and then click a new recipe.
2. Enter the recipe name in the recipe name column, select the material in the code column, and enter the corresponding weight in the weight column. After input, click **Save**.
3. To modify the recipe, double-click the recipe to be modified, and then modify the material weight to be modified. After modification, click **Save**.
4. To delete a recipe, double-click the recipe, and then click **Delete**.

## Operation

1. Select the recipe to be produced in the automatic mode, click the **Print Barcode**, and paste the printed label to the proper position of the cup.

2. Open the door of the cup feeding conveyor belt, put the cap on the cup feeding conveyor belt (the label direction is inward), and put 3 to 5 cups at the same time.

3. Click **Start**, the green light will be on when the equipment status bar is running, and the green light will be on, and the ingredients will be started.

4. After finishing, the cup will be moved to the outgoing conveyor belt. When the green light flashes, check that the indicator in the small door is off and the buzzer is always on. At this time, open the outgoing conveyor to take out the cup.


## How to clean powder feeder

1. In the manual mode, enter The **Technician Debugging - > Powder Debugging**, and select the powder to be cleaned in the powder selection column.

2. Click the **Remove** key in the position control bar to wait for the powder loading funnel to move to the material level, open the observation door, and put the clean cup on the power balance.

3. Enter a larger value in the set weight column (to discharge all the powder in the powder funnel).

4. Click the **Start** button to start removing, and take out the cup after completion.

5. If there is powder left in the powder loading funnel, continue to repeat steps 2 to 4 until all the powder in the powder loading funnel is discharged.

6. After all, the powder in the powder loading funnel is discharged, open the powder Feeding glass window to remove the inner cover and wipe the inner wall of the powder loading funnel with a dust-free towel.

7. Use a vacuum cleaner to aim at the discharge port of the powder loading funnel, and the air gun to aim at the discharge port of the powder feeder. Open the vacuum cleaner first and then the air gun. Be sure to clean the mouth of the vacuum cleaner before suction. When the air gun blows, the air pressure should not be too high at the beginning.

8. In turn, use a vacuum cleaner to aim at the discharge port of the powder feeder, and an air gun to aim at the discharge port of the powder loading funnel for cleaning (repeat steps 8 and 9 for 3 times).

9. The cleaning cycle is once a month. According to the properties of the different powder, the cleaning cycle can be appropriately prolonged or shortened.

## Powder parameter Setting

1. In the manual mode, enter **The Technician Debugging - > Powder Debugging**, and select the powder in the powder information column.
2. Click the **Remove** key in the position control bar to wait for the powder loading funnel to move to the material level, open the observation door, and put the clean cup on the power balance.

3. Input the weight in the set weight column, generally 1g to 10g. It is better to input the weight often used by the powder, and then click **Start**.

4. After powder removing, check whether the operation time is between the 60s and 200s, and if the quantity is large, extend the time appropriately; check whether the deviation value is within the allowable error value; if the time or the deviation value is not within the required range, adjust the gear.

5. There are 14 levels in the selection. The first level is the fastest and the 14th is the slowest.

6. The deviation value is within the allowable error range. If the time is too long, adjust to the fast gear; if the time is too short, adjust to the slow gear.

7. This deviation exceeds the allowable error range. If the time is too long, adjust to the fast gear; if the time is too short, adjust to the slow gear.

8. After the adjustment, repeat the test 10 times. If there is no error beyond the allowable error or the time is too long or too short, the powder debugging is completed.



## How to clean glue feeder

1. In the manual mode, enter **the technician debugging - > glue debugging**, and click the N glue key to enter the glue debugging interface.

2. Click the **Removing** key, the indicator turns green when it is in place, open the observation door, and put the clean cup on the scale.

3. Enter a larger value in the set weight column (to discharge all the glue in the glue tank).

4. Click the **Auto Start button** to start blanking, and take out the cup after completion.

5. If there is glue left in the glue tank, continue to repeat steps 3 to 4 until all the glue in the glue tank is discharged.

6. Confirm that the glue in the glue tank has been drained, turn off the air pressure, open the sealing cover of the glue tank, pour in 1 / 3 of the glass tank cleaning solution, put on the rubber gloves, and wipe the glass tank and the rubber tube in the glass tank with the cleaning solution.

7. Close the sealing cover, open the air pressure, and adjust the pressure gauge of the valve. Do not adjust the air pressure too much when cleaning. It is better to adjust the air pressure below 0.05Mpa to avoid splashing when the air pressure is too high.

8. Take off the nozzle of the valve and put it into the cleaning solution for soaking and cleaning. Put on the cleaning pipe of the valve, insert the other end of the cleaning pipe into the plastic bottle and fix it by hand. The plastic bottle should not be too small to avoid the overflow of too much cleaning solution.

9. Click the **Drain** in the interface to turn it green, open the valve to drain the detergent, make sure there is detergent flowing out of the valve cleaning pipe, and then click the Drain again to close the valve.

10. Repeatedly and intermittently click the **Start** and **Stop** to make the cleaning pipe intermittently discharge the cleaning liquid.

11. After the cleaning solution in the rubber tank is drained, add a clean cleaning solution again for cleaning, and repeat for 3 times.

12. After the third discharge, open the rubber tank, clean the cleaning liquid in the tank with a dust-free cloth, and cover the sealing cover.

13. Adjust the pressure gauge to adjust the air pressure to 0.4MPa, click **Auto Start**, make it exhaust air for 2-10min, remove the residual cleaning liquid in the pipe, click **Auto Stop** to remove the cleaning pipe, install the valve nozzle, and the cleaning is finished.

14. Replace the glue delivery pipe if necessary.

15. The cleaning cycle is once a year, or when different models of glue need to be replaced. Do not change the parameters on the glue page during cleaning.

## Glue parameter Setting 

### Adjustment

1. In manual mode, enter **the Technician Debugging - > Glue Debugging**, click the N Glue key to enter the glue debugging interface.

2. Click the **Removing** key, the indicator turns green when it is in place, open the observation door, and put the clean cup on the scale.

3. Click the **Drain Start** button to drain the glue until there is no bubble, and then click **Drain Stop**.
4. Set the test times in the manual test column to 1, the interval time to 1000, and the blanking time to 6000.

5. Click the **Big Valve**, click the **Zero**, and the blanking test, you will get a reading of the test weight, and fill this value in the reserved column 1.

6. Click the **Small Valve**, click the **Zero** and the blanking test, and a test weight reading will be obtained, which should be controlled at 0.2-0.6g,
   - If it is more than 0.6g, replace the smaller nozzle of the valve or adjust the air pressure of the air pressure gauge to reduce, and then test again.
   - If it is less than 0.2g, replace the larger nozzle of the valve or adjust the air pressure of the air pressure gauge, and then test again.

7. Fill the reading of the test in the reserved column 2 on the right, and multiply the value of the reserved column 2 by 2 times to fill in the reserved column 3.

8. Set the value blanking time in the data setting column: 1,000; waiting time 3,000; end waiting time 2,000; timeout 300,000; start waiting time 1,000; glue dropping time 0; blanking detection time 10,000; blanking detection weight 0.1.

9. The allowable error is set as the maximum error allowed by the process requirements.

10. Input the setting weight in the setting weight column, generally 5g to 20g, click the Zero, click the **Automatic Start**, and observe whether the glue error is within the allowable error range.


## Record View

1. Enter the data record interface, select the start time, end time, batching result and record type, click query, or click export to excel file.

## Alarms and Resetting


![AlarmSetting](/Image/AlarmSetting.png)



## Equipment maintenance


![EquipmentM](/Image/EquipmentM.png)



## Calibration of METTER TOLEDO Module

1. Click the scale calibration in the monitoring interface to enter the scale calibration.

2. If there is no weight on the scale, click the **Zero**.

3. Click **Start Calibration**.

4. Put the weight according to the prompts. When placing the weight, it is forbidden to touch the weight directly by hand. Take it with tweezers or dust-free cloth, handle it gently, put the weight in the center of the balance pan as far as possible, and close the observation door gently after placing.

5. Take out the weight according to the prompts and close the observation door gently.

6. After the calibration is completed, put the weight on the balance again and weigh it to see if the error is within the allowable range. Click **Record the Calibration Result** and record the calibration result. If the error exceeds the allowable error, recalibrate it.







## Video Demonstration

[![Seira-5 Demonstration](https://res.cloudinary.com/marcomontalbano/image/upload/v1586972262/video_to_markdown/images/youtube--PBjU6Q8gqEs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/PBjU6Q8gqEs "Seira-5 Demonstration")

## Support

Shenzhen Bullseye Dosing Technology Co., Ltd provides diagnostic services and the specific Support services. Bullseye will update this guide from time to time to reflect enhancements to our service and policy updates. If you have any issues during the time of operating the equipment, customers may report the issues by email or by telephone. Our Technology support would get back to you in one business day. Contact information: xxx-xxx-xxxx
