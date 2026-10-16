This is a H-bridge circuit design. The components used consists of the L293D, 2 LOGICSTATES (SWITCHES) and a DC motor.
Essentially the H-bridge circuit helps determine the direction of rotation for a DC motor by changing the direction of the current that flows through the circuit.
The H-bridge circuit usually consists of 4 NPN transistors but as a beginner I decided to use the L293D which already has the H-drive internally built.
The LOGICSTATES acted as switches alternating between high and low to reverse current( Note: In real situations making both logicstates high would make the circuit short circuit).
