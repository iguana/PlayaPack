# PlayaPack
## DIY Portable battery, solar generator, and more! 

### Why would I want to make a portable battery? can't I just buy one?

yes, you can just buy one, but:
- making one is more fun
- you can get way more features for a lot less money
- you can customize it to meet your specific needs
- have I mentioned that it's fun?

### OK, what do I need?

you need:
- LiFePO4 cells
- a battery management system (BMS)
- a case to store everything in
- ports for charging and discharging
- power converters to go from system voltage to useful voltage, like USB (QC 3.0, 2.1 Amp, USB-C, etc)
- solar charge converter - if charging from solar panels
- inverter - if you want 120v or 220V plugs
- fuses, wiring, connectors, switches, etc

## OK, how do I decide which kind of everything to get?

The first step is to decide what features you will want. What is your main use case? How much power do you need to output at once? How much energy do you need to store?

Typical LFP cells have a charge rate of 1/2 C (1/2 of their Ah capacity in Amps), and a discharge rate of 1C.

Then, you will need to pick what your system voltage will be. For most use cases, 12 volt systems are ideal. There is a great supply or 12V to USB chargers (like you'd use in a car), and are available as panel mount with dust covers for waterproof and dust proof operation (typically used in boats). Unless you need 24V or 36V output for a specific DC load, 12V is ideal. 

How many cells do I need? what size?

The most critical decision. You should pick the cell size based on 2 factors:
- the power you need to supply to your load continuously. e.g. you need to power a tea kettle (1500 watts), or a an electric trolling motor on your boat (2000 watts), or just charge a bunch of electronics (500 watts).
- how long you need to provide that power for (e.g. 10 complete laptop charges, or 20 miles of trolling motor use, or 1 night of powering a portable fridge)

Cell Wiring:
Cells wired in series - voltage adds together, the capacity is just the capacity of a single cell
Cells wired in parallel - voltage is the voltage of a single cell, but capacity and power output adds together 

LFP cells can be safely discharged at 1C. So, a 100Ah cell can be discharged at 100 amps safely, and it will last for 1 hour.

watts = volts * amps 

So, 1200 watts at 12 volts will be 100 amps. 

## BMS - Battery Management System 

To use lithium batteries safely - both to charge and discharge, you will need a battery management system. This system will provide protection of the cells from overcharging, over-discharging, and short circuits. The cells will be the most expensive component of your build, and it is critical to keep them safe. Lithium batteries can catch fire or explode, and although LiFePO4 cells are less prone to these dangers, they are not entirely immune. Some BMS are also able to balance your cells - to make sure that each cell has the same amount of energy stored. This is critical for long life and efficiency. Dome BMS have Bluetooth connectivity that allow you to monitor the state of your battery, including temperature, state of charge (% capacity), individual cell voltage. 

## Solar

Most solar panels output about 25V without a load, which is way too high to charge 12V systems. They also have an effective voltage (most efficient) at around 18-20V, so you will need something that can convert that to 14V (the ideal charging voltage for LFP 12V packs), or whatever system voltage you choose. 

### Solar Charge Controller 

Solar charge controllers that take solar panel voltage as input, and provide 12V as output, with specific support for LFP, SLA, GEL, etc batteries are available. Those using PWM (pulse width modulation) are fairly inexpensive ($10-$40, depending on max charge current). 

