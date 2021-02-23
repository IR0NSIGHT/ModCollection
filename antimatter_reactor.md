# Implementing antimatter reactors by the standard Star Trek supplies.
## Concept:
  - Deuterium (matter) and Antideuterium (antimatter) are mixed in a combustionchamber  in a controlled reaction (Matter- antimatter reaction assembly (M/ARA)) and produce plasma which is used as the  power source of the ship.
  - the reaction is controlled through use of a dilitihium crystal
  - more matter than antimatter is used in the reaction
  - Deuterium and antimatter have to be stored separately to avoid spontaneous, destructive chainreaction.
  - dilithium is (canonwise) a rare material only found sparesly throughout the galaxy. it can not be artificially created.
  - the dilithium crystal is used to prevent uncontrolled chain M/ARA, similar to a controlrod in a nuclear reactor. 
  
## Questions to answer before development:
  - can dilithium crystals expire/run out after a certain amount of usage?
  - is antimatter unstable and dangerous to handle? if so, can battle damage set it off?

    
## Side effects:
- if deuterium and antimatter spontaneously react when stored togehter, makeshift bombs can be created where logic feeds two storages together with deuterium and antimatter.
- in canon, warpcores can be ejected which offers more funky ways to use it:
  "As a safety precaution, the core could be physically ejected from the ship, should an event such as a catastrophic containment failure of the matter-antimatter
  reaction occur that could not be corrected. There were also some tactical uses for ejecting and detonating a core on purpose. The detonation could, for example,
  be used to neutralize the cascade of a subspace tear or to push a ship away from the gravity well of a black hole."
- assuming that loading/unloading the dilithium crystal into the reactors crystal slot cant be fully automated, the reactor core will have to be accessible for a     player.
- if warpcores explode after critical failure, a big explosion could be added after a ship overheated, instead of just deleting it. Would benefit immersion.
    
## Second toughts:
### Dilithium crystals:
- It might be beneficial to have the crystals decay over time of usage, with the ability to "recharge" them to elongate their lifespan. 
  This should not go on indefinetly, so that eventually the crystal dies and has to be replaced. This offers more gameplay options on gaining dilithium crystals.
### Ejectable warp cores:
- In canon, warpcores can be ejected to avoid a "meltdown" like event, and are even used for cheesy tactics like riding on the blast to escape a wormhole. Not all of   this can be easily put into the game. The most difficult mechanic is to actually allow the ejection. Right now, a vanilla ship draws its power from a big group of reactor blocks which are built into the ship itself. The game has gotten rid of docked reactors years ago for performance reasons. The amount of work to recreate a dockable power system is likely not worth it (and also not in my scope of ability). Instead what could be viable, is to instead of docking the whole reactor, just dock a tiny "core element". It could consist of a single docker and a "reactor core" block, which might also house the dilithium crystal. This leaves the ships vanilla power system in place and adds on top of it, instead of replacing it. 
The M/ARA would happen inside this core (immersion wise) and the surrounding reactor group would soak up the power. If the core gets ejected, it melts down with all its energy in a big explosion, while leaving the ship with some leftover power from the reactor "sink". In this concept the onship reactor acts like a buffer battery between reactor core and power-drawing systems. 

## Resources:
  - Dilithium:
  https://en.wikipedia.org/wiki/Dilithium_(Star_Trek)
  - warpcore
  https://memory-alpha.fandom.com/wiki/Warp_core
  
# Implementation:
### Requirements: 
- reactor can be connected to a storage
- reactor eats up resources in storage
- reactor will loose power if not fed with resources
### Nice to have:
- retextured cargo + cargospace block that become the fuel tank (non transparent cargospace)
- effects of spilling fuel when fueltank is damaged
  
