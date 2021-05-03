# Voyager2 Local Data Dictionary

The Voyager 2 dictionary contains classes that describe aspects of the Voyager 2 mission and related instruments.

Version: 1.0.0.0  
Steward: ppi

## Classes

### Voyager2
The VG2 class is the container for mission-specific metadata elements.

Attribute    | Min Occur. | Max Occur.
------------ | ---------- | -----------
[mission_phase_name](#mission_phase_name) | 0 | 1
[spacecraft_clock_start_count](#spacecraft_clock_start_count) | 0 | 1
[spacecraft_clock_stop_count](#spacecraft_clock_stop_count) | 0 | 1
## Attributes


### mission_phase_name
The mission_phase_name attribute provides the mission-defined name of a mission phase.

Type: ASCII_Short_String_Collapsed  
Units: undefined  

**Permissible Values**

Name                                    | Description
--------------------------------------- | ----------------------------
Launch | 1977-08-20 (1977-232) to 1977-08-20 (1977-232)
Earth-Jupiter Cruise | )1977-08-20 (1977-232) to 1979-04-25 (1979-115)
Jupiter Encounter | 1979-04-25 (1979-115) to 1979-08-05 (1979-217)
Jupiter-Saturn Cruise | 1979-08-05 (1979-217) to 1981-06-05 (1981-156)
Saturn Encounter | 1981-06-05 (1981-156) to 1981-09-25 (1981-268)
Saturn-Uranus Cruise | 1981-09-25 (1981-268) to 1985-11-04 (1985-308)
Uranus Encounter | 1985-11-04 (1985-308) to 1986-02-25 (1986-056)
Uranus-Neptune Cruise | 1986-02-25 (1986-056) to 1989-06-05 (1989-156)
Neptune Encounter | 1989-06-05 (1989-156) to 1989-10-02 (1989-275)
Interstellar Mission | 1989-10-02 (1989-275) to UNK


### spacecraft_clock_start_count
The spacecraft_clock_start_count attribute provides the value 
		of the spacecraft clock at the beginning of a time period of 
		interest.

Type: ASCII_Short_String_Collapsed  
Units: undefined  



### spacecraft_clock_stop_count
The spacecraft_clock_stop_count attribute provides the value of the spacecraft 
		clock at the beginning of a time period of interest.

Type: ASCII_Short_String_Collapsed  
Units: undefined  


