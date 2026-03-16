Lab 01: Hardware Acquisition & Initial Diagnostic
Device: Dell Optiplex 7040 SFF

CPU: Intel Core i5

Manufacture Date: 09-07-2016

Source: Facebook Marketplace ($30)

📦 Initial Inventory
Included: System unit and one C13 power cable.

Seller Claim: "Unit does not power on."

🔍 Phase 1: Initial Triage
Visual Inspection
Checked for physical damage to the chassis and ports. The unit is in surprisingly good condition; a few minor scuffs and internal dust, but otherwise visually sound.

Power Test
Verified the seller's claim using the provided cable. Result: No signs of life (No LEDs, no fan spin).

Component Isolation
I identified that my monitor uses the same C13 connector as the PC. I swapped the cables to determine if the issue was the internal Power Supply Unit (PSU) or the external cable.

Observation: The PC powered on immediately with the monitor cable.

Observation: The monitor failed to power on using the PC's original cable.

[!IMPORTANT]
Verdict: The C13 power cord was faulty.

Solution: Ordered a replacement power cord ($2).

<img src="C13 power cord image" alt="C13 power cord image" width="400">

Phase 2: Diagnostic Boot Up Failure 
Once the power issue was resolved, the PC powered on but failed to complete the Power On Self Test. The power button began flashing an amber/orange pattern.

<img src="blinking%20orange%20light.jpeg" alt="Blinking orange light on power button" width="400">

Technical Research
After researching Dell’s diagnostic codes, I learned that the blink pattern acts as a "Morse code" for hardware failures.

Observed Pattern: 3 amber flashes, a pause, followed by 3 amber flashes (Code 3,3).

Meaning: This code signals No Memory/RAM Detected. My guess is it's either missing ram modules completely or it is seated incorrectly.
The system is currently identifying a memory fault. Since the motherboard is communicating via these codes, the CPU and Board are likely healthy (hopfully).

Upon Opening the PC I verfied that it was indeed missing ram as the slots were all empty

<img src="PC_Internal_Checking_Ram.jpeg" width="400">







