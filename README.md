# LIthium-Ion-Discharge-Circuit

This is a simulink model to display discharge circuit of Lithium Ion Discharge circuit consisting of following main components:

1- Batteries with 3.7 Volts (connected in series to form 12 V pack)
2- Mosfet for controlling circuit
3- Relational Operator to give input signal to Mosfet based on SOC (State of charge)


Whenever the state of charge is not zero, the battery packs will keep on providing the Load. When the state of Charge becomes zero, The mosfet switches off.
