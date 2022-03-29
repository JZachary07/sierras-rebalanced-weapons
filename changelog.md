# Changelog - v0.1.0_ALPHA

## Gatling Guns
- Max projectile range to 1000 meters from 800
- Projectile velocity to 350 m/s from 400
- Fire rate to 900 RPM from 700
- Burst length to 150 rounds from 180
- Grid damage to 50 from 90
- Player damage to 25 from 33
- Headshot bonus damage removed

*Dev note: This is a 29% reduction in overall damage output versus grids. Gatling guns were extremely powerful for their cheap cost and high spammability. This change balances them for use en masse.*

- Muzzle flash duration to 25 milliseconds from 40
- Removed smoke FX for visibility
---
- Rounds per magazine to 150 rounds from 140
- Iron cost to 30 ingots from 40
- Magnesium cost to 2 ingots from 3

*Dev note: Reduction to an already-cheap cost is to balance out the ~40% loss in damage per magazine incurred by the previous nerfs.*

*Dev note: Reduction of burst size is a speculative fix of reloading mechanics. Reload downtime is balanced for in this mod but not assumed to work in all situations.*

### Gatling Gun
*All changes apply to Warfare gatling as well.*

- Reload to 1.5 seconds from 4 (unused)
- Shot deviation to 0.25 degrees from 0.15

### Small Grid Gatling Turret
- Turret traverse to 0.003 from 0.002
- Idle rotation disabled by default
- Targeting range to 500 meters from 600
- Reload to 2 seconds from 6 (unused)
- Shot deviation to 0.5 degrees from 0.3

### Large Grid Gatling Turret
- Turret traverse to 0.0025 from 0.0015
- Idle rotation disabled by default
- Reload to 2 seconds from 4 (unused)
- Shot deviation to 0.35 degrees from 0.3

## Missiles
- Launch velocity to 50 m/s from 100
- Max velocity to 400 m/s from 200
- Acceleration to 250 m/s^2 from 600
- Splash radius to 5 meters from 4
- Splash damage to 800 from 500
- Gravity enabled

*Dev note: Lower laucn speed & acceleration coupled with higher final velocity should increase the effective range of missiles without making them too deadly in fighter versus fighter engagements.*

---
- Platinum cost to 0 ingots from 0.04
- Uranium cost to 0 ingots from 0.1
- Iron cost to 10 ingots from 55
- Nickel cost to 2 ingots from 7
- Silicon cost to 0.1 ingots from 0.2
- Magnesium cost to 2.5 ingots from 1.2
- Production time to 5 seconds from 10

*Dev note: Severe reduction in ammunition costs should improve the economics of using missiles. Coupled with improved splash, missiles allow lighter ships to strip exposed systems and punch above their weight class.*

### Small Grid Rocket Launcher 
*All changes apply to Warfare rocket launcher as well.*

- Fire rate to 300 RPM from 60
- Burst length to 4 rounds from 0
- Reload time to 8 seconds from 2
- Shot deviation to 0.3 degrees from 0.1

*Dev note: Rocket launchers in general dump their ammo fast, designed to fire powerful volleys of missiles at targets, rather than slow well-aimed shots.*

### Reloadable Rocket Launcher
- No longer shares weapon definition with non-reloadable launchers
- Fire rate to 150 RPM from 60
- Burst length to 4 rounds from 0
- Shot deviation to 0.2 degrees from 0.1
- Reload time to 4 seconds from 2

*Dev note: Reloading launchers fire slower with slightly better accuracy. The less impressive volume of fire balances the ability to conduct multiple bombing runs.*

### Large Grid Rocket Launcher
- Fire rate to 360 RPM from 120
- Burst length to 8 rounds from 19
- Shot deviation to 0.5 degrees from 0.1
- Reload time to 5 seconds from 4

*Dev note: very dangerous, but high spread to limit range.*

### Small Grid Missile Turret
- Fire rate to 200 RPM from 90
- Shot deviation to 0.3 degrees from 0.5
- Reload time to 2 seconds from 600
- Max targeting range to 500 meters from 600
- Traverse speed to 0.002 from 0.0015
- Idle rotation disabled by default

### Large Grid Missile Turret
- Fire rate to 360 RPM from 90
- Shot deviation to 0.3 from 0.5
- Reload time to 5 seconds from 4
- Traverse speed to 0.0015 from 0.001
- Idle rotation disabled by default

## Autocannons
- Projectile velocity to 500 m/s from 400
- Max projectile range to 1000 meters from 800
- Grid damage to 350 from 500 (~19% DPS nerf)
- Player damage to 120 from 85 (instakill)
- Headshot bonus removed
- Fire rate to 180 RPM from 150
- Burst length to 20 from 200
- Removed smoke FX for visibility
---
- Magazine size to 20 rounds from 16
- Iron cost to 35 ingots from 25
- Nickel cost to 7 ingots from 3
- Magnesium cost to 3 ingots from 2
- Cobalt Cost to 0.8 ingots from 0
- Production time to 12 seconds from 6

*Dev note: Since autocannons almost always appear as custom turrets, and are superior to gatling guns in almost every metric, ammo costs have been increased both in quantity and rarity.*

### Autocannon
- Shot deviation to 0.25 degrees from 0.15
- Reload time to 2 seconds from 2.5

### Autocannon Turret
- Shot deviation to 0.08 degrees from 0.25
- Reload time to 1.6 seconds from 4
- Targeting Range to 800 meters from 600
- Idle rotation disabled by default

*Dev note: this makes the AC turret competitive with large grids, even on small grids. It is your best anti-air defense.*

## Assault Cannons
- Damage from 4000 to 1500
- Projectile max range to 1600 meters from 1400
- Projectile explosion FX disabled

### Small Grid Assault Cannon
- Reload to 2 seconds from 6

### Small Grid Assault Cannon Turret
- Reload to 1.5 seconds from 6
- Shot deviation to 0.25 degrees from 0.5
- Targeting range to 1000 meters from 600
- Idle rotation disabled by default
- Required construction component cost to 50 from 60
- Metal grid cost to 20 from 10

*Dev note: slight increase in the resource cost of assault cannons due to their general power level. Block health is unchanged.*

### Large Grid Assault Cannon Turret
- Reload to 2 seconds from 6
- Shot deviation to 0.3 degrees from 0.35
- Required construction component cost to 180 from 200
- Metal grid cost to 50 from 30

## Artillery Cannons
- Armor piercing damage to 0 from 17000
- Explosive damage to 4500 from 0
- Projectile speed to 400 m/s from 500
- Explosive splash radius to 2 meters from 3

### Artillery Cannon
- Reload to 4 seconds from 12
- Shot deviation to 0.25 degrees from 0.15
- Superconductor cost to 2 from 0

### Artillery Cannon Turret
- Fire rate to 90 RPM from 80
- Reload to 4 seconds from 12
- Superconductor cost to 5 from 0

## Railguns

### Small Grid Railgun

### Large Grid Railgun