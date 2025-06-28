# 👋 Welcome to the Open Source Survival Sandbox!

This project is an open source multiplayer survival sandbox game, a creative blend of Scrap Mechanic, Rust, and Astroneer. Build, battle, dig, automate, and explore in a fully destructible world that rewards engineering and creativity.

💡 I'm not an expert game developer, but I am passionate and can create textures and visual assets. By making this project open source, I'm inviting developers, artists, and dreamers to collaborate on something ambitious and unique.

Let’s build this game together, piece by piece, part by part.
#
#
Insporation:
scrap mechanic: https://www.youtube.com/watch?v=NF02KyJoXj0

rust: https://www.youtube.com/watch?v=LGcECozNXEw
#
#
# Multiplayer-sandbox-game

Multiplayer Survival Sandbox focuses on engineering-based building, strategic PvP, and deep-world exploration. Like scrap mechanic and rust had a baby.




# 🧱 Genre

 Multiplayer Survival Sandbox
 
 Focus on engineering-based building, strategic PvP, and deep-world exploration.




 
# 🌍 Setting & Theme

You are a stranded engineer in a ravaged industrial world, now overrun by hostile AI and rival survivors. The surface is dangerous, the underground is untapped—and your creativity is your greatest weapon.



# 🔧 Core Gameplay Pillars

1. 🛠️ Engineering + Building

    Build fully customized vehicles and base automation systems.

    Use logic gates, engines, pistons, sensors, AI chips, and power sources.

    All creations adhere to realistic physics-based systems and are composed of modular parts.

2. 🧟 Survival & Resource Gathering

    Gather scrap, circuitry, biofuel, and rare elements.

    Survive environmental hazards, machine threats, and hostile players.

    Manage hunger, health, and exposure.

3. 💥 PvP & Base Raiding

    Construct fortified bases with automated defenses and traps.

    Raid using your creations, tunneling machines.

    Combat relies on engineering as much as firepower.

4. ⚡ Automation & AI Systems

    Automate farming, crafting, mining, and base defense.

    Use logic gates to create your systems, vehicles, and machines.

    Integrate renewable energy systems: solar, wind, and geothermal.

5. 🚀 Multiplayer Dynamics

    Form or betray clans.

    Trade blueprints, resources, or your creations.

    Server-wide events encourage alliances—or full-scale war.

🧱 NEW FEATURE: Drilling & Subterranean Exploration




# 🌀 Underground Machines

🌌 Underground Layer

 A vast subterranean zone rich in resources and secrets:

   Rare ores (scrapie, crystalized circuits)

   Ancient AI bunkers with unique tech
   
   Lava zones, cave biomes, and buried wreckage
    
   Hidden vaults and procedurally generated dungeons

⚔️ Strategic Depth

   Tunnel into enemy bases from below for stealth raids.

   Create underground bases immune to surface scanning.

   Random collapse mechanics physics add danger to mining.


📈 Progression & Blueprint System

   Unlock new tiers of tech via exploration and reverse engineering.

   Blueprint stealing: hack enemy devices or salvage their creations.
   
   Tech paths:

🗺️ World Structure

 Surface World: Forests, ruins, factories, enemy zones, weather effects

  Underground World: Resource-rich layers, AI dungeons, secret networks

 Air & Verticality: Flying machines, snipers, orbital threats





# Parts list:
⚙️ Power & Motion Components

 gas-engine – Runs on gasoline for mechanical power (steering, pistons)

 electric engine – Electric-powered, allows finer control via logic

 Electric air compressor - Electric-powered, allows pistons and air-power blocks to be used

 Gas air compressor - gas-powered, allows pistons and air power blocks to be used

 Generator - gas-powered, creates electricity.

 bearing – Rotational joints for wheels, rotors, etc. (controlled via engines or logic)

 piston – Extendable parts for linear motion (sliders, presses, lifters)

 small wheels -

 wheels -

 large wheels -

 Slide bar - Extendable parts for dynamic linear motion, allow 2 creations to be linked by a 1-axis freely moving part.

 balloon - can be inflated to increase buoyancy using the air compressor: allows air travel or increased buoyancy for ocean travel

 small property - used for air/ water travel
 
 propeller - used for air/ water travel
 
 large propeller - used for air/ water travel

🛡️ Steering & Control

steering – Enables player-driven vehicle control

 Seat – Where a player sits; can link controls to other parts.

controller – Used for wiring connection points and logic routing

🧰 User Inputs & Interfaces

  button – Simple on/off triggers (momentary input)

  lever – Two-state toggle switch (stable on/off)

  timer – Sends signals after a delay; essential for automation loops

🛰️ Sensors & Detection

 sensor – Detects nearby objects/ ground or players; outputs logic signal

 detector – Detects nearby entities or players; outputs x.y location for tracking an entity or player: useful for the locking on turrets

🧠 Logic & Automation

 logic – Core logic processing block (AND, OR, XOR, NAND, NOR, NXOR)

  AND, OR, XOR, NAND, NOR, NXOR gates

💡 Lighting & Visual Feedback

 point light – Small omnidirectional light source

 Spotlight – Directional lighting (focused beam)

🚀 Thrusters

  thruster – Propels across surfaces or in the air; uses gas or electric power

🎯 Storage & Interaction

 chest – Inventory for items, can be integrated into automated systems
 battery - Inventory for power, can be integrated into automated systems
 oil barrel - inventory for oil, can be integrated into automated systems
 fuel canisters - inventory for fule, can be integrated into automated systems

🎯 farming & defence

 drills – resource collection, underground exploration, or damaging entities including players, can be integrated into automated systems
 
 saw blades - resource collection or damaging entities including players, can be integrated into automated systems
 
 Water jets - watering crops or pushing back entities not including players, can be integrated into automated systems.
 
 Scrap gun - single shot using scrap as ammo, can be integrated into automated systems.
 
 scrap shotgun - single scatter blast shot, using scrap as ammo, can be integrated into automated systems
 
 Scrap Gatling gun - rapid fire but inaccurate, using scrap as ammo, can be integrated into automated systems


All parts use fuel or electricity depending on the variant of the part while being used.
All parts have tiers enabling lower power/fuel costs and higher output of damage/resource collection etc, this also changes weight, buoyancy, and durability values.
All parts have a weight, buoyancy, and durability value.


# Blocks list:

Very heavy blocks:

Heavy blocks:

Normal blocks:

Light blocks:

Very light blocks:

Decorative blocks:
A variety of rounded corner blocks to wedge shapes, pipes, and tubes can mostly be made of any other block types and inherit their corresponding weight, buoyancy, and durability

 all blocks have 3 tiers: each tier amplifies their weight, buoyancy, durability value
 all blocks have a weight, buoyancy, and durability value.

Values:
Values are measured on a -10 - 10 scale 
-10 is very heavy, poor durability, poor buoyancy
10 is very lightweight, has great durability, grate buoyancy
each value is to be viewed like 

Waight:
-10:(=0==================):10

.     -9


     
Durability:
-10:(================0===):10

  .                   6


                     
buoyancy:
-10:(===========0========):10

.                1


                
# 🎮 In Summary

Fusing the creative engineering of Scrap Mechanic, the gritty survival and raiding of Rust, and the deep exploration and digging mechanics of Astroneer. Whether you're building a battle mech, tunneling under a fortress, or wiring up a fully automated AI farm, the world is yours to shape—or destroy
