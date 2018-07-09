# DHP_Flash_AB_Switch
Flash Memory "A-B" Switch for 44-pin PSOP memories such as Intel 28F400

The purpose of this circuit is to replace a single 28F400 Intel Flash Memory (or other 44 pin PSOP) with a circuit that allows for real-time switching between twomemory chips OR an equivalent memory storage.  The system should be able to switch at any time (while powered up) and should be able to be totally transparent to the Target board.

The Original chip is to be removed and the circuit is to be affixed in its spot.  The circuit should have 2 – 28F400 chips (or equivalent), a connector for a switch to toggle the active memory chip.  

Requirements
•	Should fit in defined space requirements.  A sample Target board w/ case will be supplied for test fitting / measurements.
•	Must completely function as if a normal 28F400 Flash Memory is connected to the target board.  This includes functionality such as erase / write / reading memory locations, etc.  
•	The target board should be considered auto grade so it will have a pretty wide temperature range.  The current automotive grade memory chip is …  AB28F400BX.
•	On initial power-up, one of the chips should be automatically switched active for target board.
•	The CS pins (see diagram) are to allow for a switch input to toggle between the memories.  User should be able to know which chip is active so would probably recommend using a double position switch ? 
•	Memory Switching should be possible at any time while Target is powered on.  The only rule to this is that the circuit should take basic care to ensure that a chip is not in the middle of an operation when being switched out.  
•	The circuit should be easily mounted on the target board in the field with standard tools.  Using a pin header to affix to the target is probably a good way to accomplish this.  The bottom of the circuit could then fit onto the header pins
