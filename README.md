# Current_Mirror_ACD

The current mirror is an analog circuit that senses the reference current and generates the copy or number of copies of the reference current, with the same characteristics. The replicated current is as stable as the reference current source. The replicated current could be the same as the reference current (Icopy = IREF), or it could be either multiple or fraction of the reference current.<br> I<sub>2</sub> = [ (W/L)<sub>2</sub>/(W/L)<sub>1</sub> ]*I<sub>ref</sub> 

## PROBLEM STATEMENT
<br>
<strong>Design a common source stage with current source load (implement using current mirror) for the following specifications:</strong> <br>
  <br>
  &emsp;Gain (A<sub>v</sub>) = 20 <br>
  &emsp;Power budget < 20 mW <br>
  &emsp;Supply voltage (V<sub>dd</sub>) = 1.8 V <br>
  &emsp;Threshold Voltage (V<sub>th</sub>) = 0.5 <br>
  &emsp;U<sub>n</sub>C<sub>ox</sub> = 100 uA/V<sup>2</sup>  <br>
  &emsp;U<sub>p</sub>C<sub>ox</sub> = 200 uA/V<sup>2</sup>  <br>
  &emsp;Output Swing Limit = 0.5 peak to peak <br>
  &emsp;λ<sub>1</sub> = 0.1 V<sup>-1</sup> <br>
  &emsp;λ<sub>2</sub> = 0.2 V<sup>-1</sup>

## SCHEMATIC
![current_mirror](https://github.com/SahilPrabhu/Current_Mirror_ACD/assets/92974277/5e0b3056-af67-4e3d-a8ef-9807e3a03172)


## DC ANALYSIS
![dc_analysis](https://github.com/SahilPrabhu/Current_Mirror_ACD/assets/92974277/aef43d4a-d62a-44ad-adda-dd4d30815268)
<br>
We can see the transfer characteristics of M1 NMOS in the graph which shows that it is in saturation.

## TRANSIENT ANALYSIS
![transient_analysis](https://github.com/SahilPrabhu/Current_Mirror_ACD/assets/92974277/c07758da-3e44-4e14-9fcc-c65556034a2f)
<br>
When we compare peak to peak voltage of output we get the following values:<br>
<br>
  &emsp;upper peak - 1.01 V <br>
  &emsp;lower peak - 810.09 mV
