# Electricity Distribution, Generation and Renewable Energy Guide
## v 1.02
![Nethope Logo](i/NethopeLogo.png)

## Introduction

![Power pylon in Africa](i/PowerMast.png)

Whether it’s an office, clinic, school or the residence, electricity is an essential utility. Unlike developed countries, access to clean, reliable and safe power in the global south can be difficult and in many cases expensive. 

Access to a reliable power supplies is essential to humanitarian programming. Power is needed for lighting, cold chain, heating, communications and to run IT systems. The provisioning of safe power is also very challenging as materials in some places will be of poor quality. Lack of skills can lead to poorly installed systems which pose a serious risk to equipment and people. 

This guide has been written to improve the knowledge people managing humanitarian programmes about electricity supplies. Whilst it contains a lot of best practice advice and tips, this guide is not intended to be a detailed electrical installation guide. Electrical installations should always be carried out by qualified electricians who have demonstrable skills. 

Whilst it’s very unlikely that the high standards required under law (IEE for the UK) will be reached, aid organisations have a responsibility to all of its team to provide a safe working environment. This guide illustrates electrical best practices.

This guide also includes some planning tools to help you estimate energy needs for any site. Good planning will enable you to select the correct size generator or solar system for the site. 

The first edition of this guide was created by Mark Hawkins for Merlin in 2012. It has now been shared freely with the Nethope community to help all members to create a safe working environment for Aid Workers and beneficiaries. I hope that in the near version, that this guide will be replaced with a more up to date version incorporating more information about renewable energy. 

Mark Hawkins<br>
Global Humanitarian Technology Manager<br>
Save the Children International</br>
December 2018

## Contents
1. [Introduction](#Introduction)
2. [Safety](Safety)
    - [Electricity Kills!](#electricity-kills)
    - [Fire Risk!](#fire-risk)
    - [Working practices](#working-practices)
3. [Power Supplies](#power-supplies)
    - [Sources](#sources)
    - [Single Phase](#single-phase)
    - [Three Phase](#three-phase)
    - [American Standards](#american-standards)
4. Power Distribution
    - Circuit Design
    - Grounding
    - Quality of parts
5. Site Planning
    - Utility Power
    - Stored Energy
    - Selecting the correct generator
    - The energy planning toolkit
        - Generator Sizing Tool
    - Cable sizing tool
6. Generator Management
    - Daily routines
    - Weekly Routines
    - Monitoring
    - Servicing
    - Spares & Consumables
    - Change Management
7. Solar Energy
    - Planning
    - Typical system design
    - Lightning Protection
    - The Load
    - Rugged design
    - Change Management
    - Maintenance and sustainability

## Safety
This chapter highlights some of the risk experienced in NGO sites every day. Whilst there are a few extreme examples of bad practice or poor design mentioned, the majority of the problems illustrated have been collected from a wide range of sites over the past fifteen years.
### Electricity Kills!
In the aid sector, the provision of a safe and efficient electrical system is not treated as a priority. As a result, severe risk of electrocution will exist in the office, the bathroom and the bedroom. There have been reports from the field where team members have received electric shocks whilst operating equipment. In one severe case, an aid work was killed in one agency when a team member was electrocuted in a bathroom

Here are some examples of defects which are presenting danger to people;

 | Example | Description |
 | --- | --- | 
 | ![Exposed wall socket](i/DangerousWallSocket.png) | A wall socket was missing in a bedroom leaving two bare wires exposed. A visitor to the room not aware of this cable could have easily touched it and may have received an electric shock. |
 | ![Dangerous powerline](i/DangerousPowerline.png) | <p>A power line from the national grid comes over the wall. The power cables are not insulated. Under normal circumstances this would not be an issue as grid cables arrive at roof level well out of the reach of people.</p><p>In this example, the cables pass within centimetres of a roof ladder. There are two significant risks here</p><ul><li>People ascending the wall ladder to deal with communications equipment is very likely to come into contact with the live cable.</li><li>If the ladder comes into contact with the cable, it becomes electrified. The bottom of this fixed ladder is close to a busy passageway.</li></ul> |

### Fire Risk!
Poor quality electrical installations can cause fires through short circuits. There is one extreme example where an electrical fault in an ammunition store resulted in major explosions in Brazzaville (Republic of Congo) in March 2012. More recently in 2017, an NGO suffered a series fires it its country head office (south Sudan) because the cabling used was too thin.

Fires can happen as a result of overloading of circuits, poor storage of flammable liquids, paints, gases as solids adjacent to switches and generators. The breakdown of cable insulation can lead to fire. Rodents in roof spaces are well-known for eating insulation. Once the plastic insulation has gone, roof fires can easily occur.

### Working Practices
Unskilled staff working with poor quality tools will also be at risk. In developing countries, electrician’s tools are normally of a poor quality and poorly insulated. 

### Conclusion
Now that you have read all the horror stories about what could happen if we neglect the concept of safe electrical practice, please read on!  The rest of this guide explains how safe and reliable electricity can be achieved. 

## Power Supplies
A stable power supply is essential for the smooth running of appliances in offices and residences. Where supplies are unstable, measures will be needed to protect equipment and in some cases to ensure continuity of supply during power cuts.

Supply voltages will be different depending upon the country and circuit type used. In most places, voltages will be 220V, but in the USA, South America and the Caribbean, it will be 110V. Some circuits will contain a mixture of voltages, which means a lot of care needs to be taken by electricians when setting up power systems.

### Sources
In general, power will come from one of three sources, the local grid, and a generator or from battery (charged via a battery charger or a solar system). For smaller sites which rely on battery storage, it’s often better to set up as many systems as possible to run on 12v. Where needed, inverters can be used to convert 12V DC to either 220V or 110V AC.

Quite often, a combination of sources will be required for example a backup generator may be needed for places where grid power is unreliable. Where there is no grid supply at all, two generators will probably be needed.

### Single Phase
Most people direct experience of electricity will be in either the home or office where single phase power is normally used. In Europe, Africa Asia and the Middle East, the voltages will be 220V AC, but in the USA, South America and the Caribbean, its 110V AC.

Single phase supplies are simple and consist of two lines to supply power (Neutral and Live). A third Earth cable is also included for safety.

Smaller generators (typically less than 9 KVA) will produce single phase power.

### Three Phase
Almost all utility companies will generate electricity using three phase power. Whilst single phase is normally supplied to smaller domestic buildings, larger buildings may be supplied by three phase power.  The output from larger generators will also be three phase.

Three phase power consists of three lines each providing 220V AC. A clear understanding of how these lines relate to each other is essential as if mistakes are made in setting up circuits, it’s possible to supply 380V AC to a circuit and cause a lot of damage. 

If three phase power is supplied from a generator, the site circuit must be designed in such a way so that the total load from all electrical items on the site is equally distributed across all three phases. 

Over the years, there have been plenty of examples where a single output on a three phase generator has been used. This will significantly shorten the life of the generator as the wear on the internal parts will not be even. The alternator is the part of the generator which creates the electricity. As internal parts rotate, if only one phase is used, resistance will only be encountered for just 1/3rd of each rotation. This is uneven resistance is what causes the excessive wear on bearings and windings. 

The following diagram shows a typical output from a three phase supply which consists of four cables. A neutral line is common to the other three lines. So a link between neutral and any of the three “Live” lines will deliver a 220V AC Supply. 

![Output of three phase generator](i/ThreePhaseOutput.png)

**BEWARE!!!**
**Never connect equipment between the “Live” lines (1+2, 1+3, or 2+3) as the respective voltage will be 380V AC. The correct way to provide supplies will always be a combination of one “Live” line and “Neutral”**

Alternating Current (AC) from either a generator or a utility supply will alternate between +220V and -220C up to 60 times per second. The transition from positive to negative follows a “Sine Wave” pattern.

In a three phase circuit, the outputs from the three lines are not synchronised. They are in fact separated by about 1 third of a cycle (which is the same as one third of a rotation on the generator).

The diagram below demonstrates clearly the relationship between the lines. 

![Three phase output sine waves](ThreePhaseOutputSine.png)

If measurements are taken between any of the lines and neutral, the maximum voltage reached is 220V AC. This is shown by the red dotted line. 

The blue dotted line shows a measurement between the red line and the blue line where the blue voltage is at +220V and the red voltage is at -160V. This means that the total difference in voltage between the two lines is 380V AC.

### American Standards
Power generation in the USA starts out in the same way as it does for the rest of the world as three phase power. In a typical domestic residence, two lines of 110V AC is supplied. The twin outputs is derived from a 220V AC single phase line via a centre tapped transformer which would be located in a neighbourhood substation. The diagram below shows how a centre tapped transformer modifies the output. 

![How centre tapped transformer modifies electrical output](i/AmericanTransformerOutput.png)

The single phase input of 220V AC is feed to the primary coil in the transformer. The secondary coil has an identical number of winnings but a third cable is joined to the central winding. This results in twin outputs of AC which are exactly in opposite phases. So any device connected between the neutral and   either line will be supplied with 110V AC. By connecting directly between Lines 1 & 2, 220V AC is available. 

The following graph shows the relationship between both lines and how two lines of 110V can be used to provide 220V AC

![110 V to 220V AC Sine graph](i/110Sine.png)

It is common practice to supply both lines to domestic sites in the USA. In general, lines will be split up between floors where 110V is supplied to sockets and lights. Heavy duty appliances such as water heaters and air conditioning are normally hard wired into the circuit and supplied 220V AC by using both lines. 

For emergency teams deploying to places where USA circuits is used, it is often believed that step up transformers are needed to convert 110v to 220V. This is clearly not the case. As long as both lines can be clearly identified, a separate circuit can be used to supply 220V. Be sure to use a different type of plug and socket so that 110V equipment cannot be accidentally connected to the 220V supply. 

## Power Distribution
So far, we have focused on providing electricity which is stable from a number of sources. The business of getting electricity from its source to where it’s needed is also important. If electrical circuits in a site is poorly designed or incorrectly installed, circuits could become overloaded thus presenting a fire risk, energy loss or in severe cases a risk of electrocution may exist. 

### Circuit Design
The diagram below shows an example of a typical site which has access to two supplies (electricity from a local utility company and a back-up generator)

![Typical site circuit design](i/TypicalSiteCircuitDesign)

Three phase power is used in the example which is fairly typical for medium to large offices. In smaller buildings (Typically residential settings), single phase is used. The following notes explains further about each key feature of the circuit. 

* **Local Utility Supply**: The cable which supplies power to the site is normally the responsibility of the utility company. They will own all cabling including the electricity meter up to the first junction box. Local standards vary, but in general, the first junction box will belong to the utility company and all circuits downstream is the responsibility of the customer. The above diagram is simplified and shows the utility power connected direct to the changeover switch.

* **Generator**: The generator in this example provides back up power to the site. It has been sized up to match the demands from the loads throughout the site. Like the utility supply, electricity is three phase. 

* **Change over switch**: The purpose of this switch is to make sure that both supplies (Generator and utility power) are not supplied to the load simultaneously. This switch normally has three positions which are supply 1, supply 2 and isolate. It is important that the switch is rated to match the total load of the circuits. For example, if the total load is 18KW, then maximum circuit current will be: 
    * 18KW = 6KW per phase (6000 Watts) 
    * 6000W ÷220V = 28Amps per phase
Remember, it’s the load that you need to match and not the size of the generator. It’s possible that greater loads may be drawn from utility power than the generator. In more advanced countries, the utility supply will be delivered via a master fuse box. The changeover switch rating should be equal to or greater than that of the utility fuse. 

NOTE: It has been known for unqualified electricians to place a changeover switch into the circuit between the utility supply and the electricity meter. This means that at times when utility is not available, power would be supplied from the generator to the circuit via the meter, thus meaning that the site would be charged by the utility company for power from the generator. 

* **Distribution / Fuse panels**: The key purpose of a fuse panel and its fuses or circuit breakers is safety. Circuit breakers or fuses are sized up to prevent cables and equipment from becoming overloaded. 

    * **Main distribution panel (3-phase)**: The main distribution panel splits the phases into three separate circuits and where needed, a three phase circuit is provided as well. In this example, the generator can produce a maximum of 25A per phase. To avoid overloading, circuit breakers are arranged to provide three single phase outputs rated at 20A and one three phase output of 15A (5A per phase). 

    * **Secondary Fuse Panels**: further panels are placed further down line. These can divide up loads into further circuits. The example shown on Phase 3 shows that the circuit has been divided up into four sub circuits. The total load must not exceed 20A. Circuit breakers could be set to divide the load as follows:

        * Security lights: Total = 400W (2A); 3A assigned for future expansion. 
        * Heater = 2KW (9A); 10A assigned
        * Lights = 200W Total (1A): 2A assigned
        * Power sockets: 5A. This is the remainder of the 20A left over. 1.1KW maximum loading permitted. 

* **Cables**: The cables used to link power sources and switch panels must be sufficiently large enough to carry the load. Larger cables will be needed closer to the supply. For a 25A load, 6mm cable will be needed, but further down the line where the maximum load is 5A, 1mm cable will be sufficient. The cable sizing tool should be used for the best results. 

For longer cable runs, thicker cables should be considered as they will reduce power losses. 

### Grounding
In developed countries, laws governing grounding of electrical equipment is very strict and have been in place for many decades. It’s a well-established fact that faulty electrical equipment which is not grounded is likely to be lethal.

Grounding is essential as if there is an electrical fault in an appliance, electricity goes to earth thus preventing anyone using the faulty electrical item from being electrocuted.

In many developing countries, electrical circuits may be in poor condition and may not have grounding in place. It’s essential for safety of all staff to ensure that circuits are checked out and grounding put in place.

In a well-designed circuit, grounding rods should be close to where power is being supplied. In a domestic or small office setting, one central grounding rod is provided per building and will cover all of the distribution panels inside the building. In larger offices, more than one grounding rod will be needed.

From the distribution panels in single phase circuits (220V & 110V) three cables will supply all sockets and lights. The Live and Neutral will be used to power all appliances. A third cable will be used to link wall sockets and light fittings to the ground system.

Three pin sockets must be used throughout the site so that equipment which is supplied with the appropriate cords will also be grounded.

Extension cables are often a weak link in a circuit as if they are used often, they can become worn. Good quality extension cables must always be used and must away include a grounding core cable.

In addition to providing local grounding rods for each building, each generator must also be grounded with its own independent rod.

### Quality of parts
It is paramount that good quality components are procured for electrical circuits. In developing countries, many items on the local market will be of Chinese origin and made from very poor quality weak plastic. Covers to sockets and switches will break leaving exposed circuits which will present an electrocution hazard to people.

Extension leads with multiple sockets are used in great quantities throughout most sites. Not only do they transfer power from a socket to a number of appliances. Poor quality extension leads must be avoided as they will present a number of hazards as follows:

* Damage to covers will expose live parts.
* Thin cables can be overloaded and present a fire risk.
* Sockets may be a little bigger than the sockets which will lead to arcing. If a computer plug is placed in a lose socket, unsaved work may be lost when the plug falls out of the socket.

 
## Site Planning
The previous sections of this guide has focused on sources of power supplies, the differences between single and three phase, USA power supplies and safe power distribution inclusive of grounding.

This section deals with the practicalities of designing a power supply system for a field site. The best way to approach the task of providing power is to establish the quality and reliability of the local utility power and then define what back up capacity may be needed.

A number of tools are available in the energy planning toolkit to make the task of planning easier.

### Utility Power
The quality and reliability of a power supply from the local utility company should be taken into account before signing the lease on any building. In many developing and middle income countries, power cuts will be frequent. Power supplies can be more reliable is some parts of town than others. 
The overall aim is to ensure that there is enough power available at all times to enable an office to operate normally, or a residence to be comfortable.

The following table sets out four power supply scenarios and potential solutions.

 | Utility power status | Solution |
 | --- | --- |
 | Stable utility power with electricity available 24 x 7. Power cuts very infrequent with no seasonal variations. When there are power cuts, they last no longer than a few minutes. | Minimum investment on alternative power. Desktop computers and network gear to be provided with UPS. |
 | Power supply reliable and stable, but subject to a small number of power cuts each week ranging from 10 to 120 minutes. No seasonal variations | UPS for network items and desktop computers. Battery bank and inverter to supply power to the site in the absence of utility power. |
 | <ol><li>Power cuts frequent but not exceeding 50% of the working day.</li><li>Reliable power for part of the year, but during a 4 month season, power supplies are unreliable.</li> | UPS for network items and desktop computers.<br/><br/>Standby generator to run the officer for periods when the utility supply is offline. |
 | Utility power is non-existent or very unreliable. | UPS for network items and desktop computers.<br/><br/>Two generators with the ability to use utility power when it’s available (assuming that it can be trusted!) |

 It is fairly obvious from the table that the more unreliable the local utility supply is, the more money which needs to be invested to ensure that the site is adequately provisioned. The following pages will cover the specification of back up supplies in more detail. 

### Stored Energy
For offices where power cuts are infrequent and short, standby power can be provided by using a stored energy system. The design is fairly simple and consists an inverter and a battery bank. 

When normal power is supplied, the inverter will keep the battery bank topped up. During power cuts, the inverter will convert the battery energy in to 220V AC to keep the office running. 

![Stored energy solution](StoredEnergy.png)

The approach to designing a stored energy system is similar to methods used to design a solar system. The key factors to consider are:

* The inverter must have enough capacity (in amps) to run the loads in the office
* The battery bank must have enough capacity (in amp hours) to run the inverter for the required period of time. 
* Circuits should be laid out so that non-essential items such as air-conditioning and water heaters are not connected to a circuit supplied by the invertor. 

Here is an example:

 > **Requirement**: An office requires a back-up power system which has enough capacity to run an essential load of 2.5 KW for three hours. 

 > **Solution**: 2.5KW = 2500 W, 2500 W ÷ 220V AC = 11.36A (Round up to 12A). The inverter must be capable of delivering a load of 12A. Most inverters are specified in KW. 

 > 2500W ÷ 12V= 208A. This means that cables connecting the inverter to the battery bank will need to be large enough to support such a large current. 

 > Given that the DC current is 208 A, to run the office for three hours, the calculation to use is 208 A x 3 Hours = battery capacity of 624AH. 

Stored energy solutions can also be used in combination with generators in places where power cuts are more frequent. The benefit to this approach is that overall fuel consumption can be reduced and generator usage at night can be avoided.

### Selecting the correct generator
Choosing the correct generator is not as simple as looking at the budget available and buying the biggest and hoping for the best. The generator needs to be matched closely to the load which it is expected to supply power to. A generator sizing tool is included in the energy planning toolkit to assist teams choose the right size generator. 

If a generator is too small, it will become overloaded frequently and the office will not run efficiently. Where capacity is greater than needed, an underutilised generator will be expensive to run and in the longer term, there could be problems with the engine.

One of the most frequent mistakes made is where three phase generators are specified but only one phase is out to use. This is extremely bad practice and can significantly shorten the life of the alternator part of the generator. 

Where possible, only single phase generators should be procured as most buildings are wired up as single phase. In many local markets, choices are limited. It’s not unusual to be faced with a situation where all generators over 5KVA are three phase. Where this is the case, the best solution is to rewire the office so that loads are divided between the three phases. 

As a rule of thumb, it is best to target selecting a generator which has around 20% more capacity than the maximum load (Maximum load does not necessarily mean total load as all electrical items on side may not be used simultaneously). The generator sizing tool has been designed to work out average loads for day and night. In places where two generators are needed, a significant difference between day and night loads could lead to generators of different sizes being selected. 

Other important things to consider:
* **Fuel**: Most generators will run on diesel, but some smaller generators will run on petrol. Where possible, favour diesel over petrol as diesel is safer to store and is often cheaper. Diesel engines are more basic than petrol engines and therefore less likely to fail. 

* **Make/quality**: Generators are bulky and heavy, therefore is very likely that generators will be purchased in the same country. Well-known brands such as FG Wilson, SDMO and Perkins. More obscure makes especially from China should be avoided as they are often built to a poor standard. 

 > Some generator sets are often assembled in country by local companies using internationally branded components. For example, if a locally built generator consists of a Caterpillar engine and a GEC alternator, then is quite likely to be a good generator and suitable for use by NGOs.  This practice is fairly common in Europe as well, for example, FG Wilson uses Perkins engines.

* **Supplies**: Generators will need a constant supply of consumables such as air, fuel and oil filters. Ensure that there are supplies of genuine parts available in country for the generator to be purchased. 

* **Location of generator**: The eventual place where the generator will be set up will probably involve some compromises. The location for the generator must be as close as possible to where power is being consumed. If the generator is placed too far away from an office, long cables will introduce some voltage drops, possibly enough to stop freezers from working correctly. 

 > Generators produce a certain level of noise, so should be placed as far away as possible from meeting rooms, sleeping areas etc. Further measures such as sound proofing enclosures and walls made from sand bags will also help to reduce noise. 

 > Exhaust from a generator will contain carbon monoxide which can kill. Where generators are situated within generator rooms, exhaust MUST be piped to the outside. The siting of generators and generator rooms should also be located in places where prevailing winds will not blow fumes into office workspaces and accommodation areas. 

* **Servicing**: When procuring a generator, establish the supplier’s competency to service the generator. For smaller programmes who do not employ mechanics, outsourcing servicing should be considered. See the managing generator section for more detail.

* **Security/fuel store**: Fuel, parts and even the generator itself should be considered at high risk of theft, especially if the generator is located outside of the main confines of the compound. The generator should be located in a secure place. Spares for the generator should be kept under the control of a warehouse and never in the same room as the generator. 

 > Fuel must be stored in a well-ventilated place and never inside a generator room. There should be no fire risks or electrical items in the fuel store. 

 > Large fire extinguishers must be kept close to the generator and the fuel store. 

 > An emergency remote fuel cut-off handle should also be considered so that fuel can be isolated to the generator from outside of the generator room. Mechanical remote options are easy to source. 

* If local utility power is so unreliable that a generator needs to run for more than 12 hours a day, two generators must be provided. 

### The energy planning toolkit
In some cases, the main energy source for a site will be from a generator, solar system or from a national power company. Where national power is unreliable, a backup generator may be needed.

The energy toolkit consists of two excel spread sheets. One to estimate the correct size of generator needed, and the other to estimate the hardware needed for a solar power system.

When using the planning tools, the first task is to list all of the equipment on site and note how often the equipment is used. Additional information will be needed such as altitude and availability of sunshine during the day. Each tool will present an analysis of power requirements which should be sufficient to specify the best power solution for the site. 

### Generator Sizing Tool
The screen shot below is of the input page. This is where all electrical items will need to be listed.

![Generator sizing tool](GeneratorSizingTool.png)

The following colour convention is used in the tool:

 | Colour | Meaning |
 | --- | --- |
 | Light Orange | In these columns select correct option from drop down menu. |
 | White | Data entry area |
 | Light Blue | This column can be edited if no information has been calculated |
 | Light Green | Results – please do not edit! |








