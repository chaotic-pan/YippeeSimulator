# Unreal Game Engine Programming - Particle Project

## Contribution of Eve Schütze

- added textures to house map
- decorated interior of house
  
- fog particles 
- ember particles
- falling leaf particles 
- magic ring particles 
- added glowing eyes particles to skull model
- dripping blood particles + blood puddle overlay
  - utalising one looping particle
  - change the material to use a colour assigned through the particle not the material 
- rune circle texture particle
- steaming particles to skull model
  - overlay material on the skull to give an orange outline on the mesh
  - using the mesh as a spawn location for the particles & then animating them
- particles tracing outline of skull model with the mesh spawn location

- split floors from walls
- house floors
- importing models & respective textures for the interior
- changed default level

### During the individual process
- main menu UI + functionality

## Contribution of Liz Kintzel

- build the house map
- loaded in majority of prop models
- turned all prop static meshes into blueprints 
  - combining of models that came in separate meshes
  - appropriate sizing and rotation to fit into scene
  - added light sources to all lamp-like models
- fire particles (inside fireplace)
- candle fire 
  - animated/distorted material
  - singular particle that "displays" material
  - combined with candle meshes and light sources to make complete candle blueprints 
- portals
  - one version that constantly loops
  - one version that just runs once and then disappears
  - entering portal teleports player back to entrance + spawns new exit portal there
- confetti particles
  - created new material that is similar to default material, but not lit
  - changed the default 3rd person game gun to shoot confetti instead of ball
  - added new YIPPEE! sound effect instead of the original gun sound 
  - added setting to gun blueprint, that lets it easily be switched between default gun and confetti gun
  - confetti gun still shoots a ball which makes it possible to push/break objects, however, ball is invisible to make it look like the confetti blast is interacting with the surroundings
- chaos destruction fracturing of skull mesh 
  - can be destroyed by gun (both types)
  - created Material for skulls to make the shattered fragments disappear after a few seconds
- Landscaping 
  - made graves in the backyard
  - added some height variation to landscape beyond the fence
  - painted texture blend variation
- added Trees beyond the fence with PGC Graph
