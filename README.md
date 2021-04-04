# Odour station

Hardware for delivering odours. Can be modified so that the second manifold controls for odour source direction, instead of providing additional odour types. Will Dickson designed the PCB for controlling the solenoid valves. Will Dickson wrote the [original firmware and software](https://github.com/willdickson/switchx7), which I [slightly modified](https://github.com/hanhanhan-kim/switchx7) so that valve command signals can be copied to the expansion port and streamed to an acquisition device, such as a DAQ. 

TODO: Insert CAD render here

## Hardware

### BOM 

In addition to standard electronics equipment and access to a 3D-printer:

| Item | Price (USD) | Quantity | Source |
| ---- | ----------- | -------- | ------ |
|      |             |          |        |
|      |             |          |        |
|      |             |          |        |

### Hook-up

The hook-up is straightforward. To connect the solenoid valves to the PCB, crimp the JST-PH terminals onto the leads of the valves. The valves do not possess polarity. Alternatively, if crimping the terminals is too cumbersome, simply splice [these pre-crimped JST-PH wires](https://www.sparkfun.com/products/8671) onto the solenoid leads. See the solenoid controller’s [documentation](https://github.com/willdickson/teensy3x_solenoid_driver) for remaining details. 

### Assembly

Print all 3D-printed components. 