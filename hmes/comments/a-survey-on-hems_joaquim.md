# A Survey on Home energy Management System

## Context
* Building are one of the major energy consuming sectors.
* Save energy in this sector has a commercial and environment gain

## Home Management System
* The HEMSs are used to,
  1. Monitoring real-time consumption
  2. Schedule appliances operation
* Traditional power grid has evolved to a *smart* paradigm
* Building are responsible for around 40% of worldwide energy consumption.
* The conceptualization of HEMSs involve several aspects, including their definition, characterization and overall architecture, as well as their underlying purpose in household environments.
* Intrinsically linked with the characterization of HEMSs are:
  1. Operation goals
        * Minimizing consuming bill
        * Reduce the carbon emissions
        * Achieving a target load profile
  2. Strategies to achieve the goals
        * How to schedule individual appliance
        * Deciding which unnecessary loads should be turned off
  3. Managing household appliances
  4. How they are individually modelled
* With the development of advanced metering infrastructure(AMI), remote control and automation systems, we can managing power resources at house-hold level.
* HEMSs components
  1. Sensing and measurement devices
  2. Smart appliances
  3. User interface
  4. Central platform. It receives smart meter information and adopts a scheduling mechanism, usually computed via an optimization approach, assuming a given performance index.
* Centralized HEMSs
  > The grid centralized management platform schedules demand-side electricity and generator operations in order to optimize specific criteria, for instance operational cost, or peak-to-average ratio.
* Distributed HEMSs
  > Distributed-based approaches rely on several independent decision-making entities to plan demand-side and grid operations.

## Household Appliance Models
* Electrical devices, each with its own specific characteristics in terms of energy consumption and usage profile.
* Appliances are distinguished between *controllable* and *non-controllable*(scheduling is not available).
    > [37] A. C. Batista and L. S. Batista, ‘‘Demand side management using a
    > multi-criteria -constraint based exact approach,’’ Expert Syst. Appl.,
    > vol. 99, pp. 180–192, Jun. 2018. [Online]. Available: http://www.
    > sciencedirect.com/science/article/pii/S095741741830054X
* A broader categorization is defined in,
    > [8] M. Beaudin and H. Zareipour, ‘‘Home energy management systems:
    > A review of modelling and complexity,’’ Renew. Sustain. Energy Rev.,
    > vol. 45, pp. 318–335, May 2015. [Online]. Available: http://www.science
    > direct.com/science/article/pii/S1364032115000568
      - Uncontrollable loads. Considers loads that provide and added value to residents, sometimes completely controlled by users(tv,  computer or sound systems).
    - Curtailable loads. Energy consumption can be adjusted mid-operation, usually with no significant impact to residents confort (dimming indoor artificial illuminance during day-time as a function of daylighting)
    - Uninterruptible loads. They should run a complete cycle (Dishwasher, clothes washer or dryer machines). 
    - Interrumpible loads. Examples include plug-in hybrid electric vehicles and other rechargeable devices. 
    - Regulating loads. Heating, ventilation and air conditioning(HAVCs)
    - Energy storage
* Common controllable household appliance referenced in the literature (over 15 references each)
  1. Washing machine
  2. Dishwasher
  3. Electric Vehicle
  4. Dryer Machine
  5. Air Conditioning
  6. Water Heater
  7. Light spots
* Sources of uncertainty in HEMSs are:
  - Appliance operations needs
  - Appliance consumption
  - Local micro energy production 
  - Utility grid prices

## Scheduling
* Improve energy efficiency and residents' comfort
* Methods and techniques
  - Mathematical optimization
  - Heuristic and metaheuristic methods
  - Model-based predictive control
  - Machine learning 
  - Game theory approach
* Criteria
  - Electricity bill
  - Distribution system losses
  - Peak load. utility companies encourage customers to minimize the peak demand or even to achieve a particular load profile, which benefits the grid management.
  - Carbon emission
  - Customer comfort
  - Social welfare
* xD