# Stereo_Speaker_V2
ECE5 extra credit assignment tasked students with designing a PCB from a provided mono-amplifier schematic. This is an extended version with the following modifications:

Converted the mono circuit into stereo, added a band-pass filter (80Hz-16kHz), 9V regulator, LED power indicator, and integrated with a 100W USB-C PD module from Aliexpress to allow for 100W charging/discharging for mobile devices if needed.


Reasoning: 

Band-pass filter was used to compensate for the extra-long audio cable

9V regulator was used to allow for other power sources besides the in-class 9V alkaline battery -- allowed for Li-ion battery pack to be used and for the use of the 100W USB-C module)

LED power indicator was used to reduce power loss on the LDO and was a nice-to-have feature

100W USB-C module was added because I wanted a battery bank, and I realized I could make a speaker and portable battery at the same time.
