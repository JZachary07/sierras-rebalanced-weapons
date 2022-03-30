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
---
- Required steel plate cost to 20 from 10
- Optional steel plate cost to 50 from 30
- Required construction component cost to 20 from 30
- Optional construction component cost to 20 from 10
- Bounding box from 3x3x3 to 1x3x1
  - This change is not backwards-compatible and requires duplicating the cubeblock definition while hiding the original in build menu.

## Missiles
- Launch velocity to 50 m/s from 100
- Max velocity to 400 m/s from 200
- Acceleration to 150 m/s^2 from 600
- Splash radius to 5 meters from 4
- Splash damage to 600 from 500
- Gravity enabled

*Dev note: Lower launch speed & acceleration coupled with higher final velocity should increase the effective range of missiles without making them too deadly in fighter versus fighter engagements.*

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

- Fire rate to 360 RPM from 60
- Burst length to 4 rounds from 0
- Reload time to 8 seconds from 2
- Shot deviation to 0.5 degrees from 0.1

*Dev note: Fast fire rate, improved top speed, and questionable accuracy make for effective burst damage strikes.*

### Reloadable Rocket Launcher
- No longer shares weapon definition with non-reloadable launchers
- Fire rate to 300 RPM from 60
- Burst length to 2 rounds from 0
- Shot deviation to 0.2 degrees from 0.1
- Reload time to 1.5 seconds from 2

*Dev note: Shorter burst versus other launchers, but better accuracy for repeat bombing runs.*

### Large Grid Rocket Launcher
- Fire rate to 360 RPM from 120
- Burst length to 8 rounds from 19
- Shot deviation to 2 degrees from 0.1
- Reload time to 3 seconds from 4
- Optional steel plate cost to 40 from 15

*Dev note: high spread limits range, but large volley and rapid reload effectively splashes area.*

### Small Grid Missile Turret
- Fire rate to 240 RPM from 90
- Shot deviation to 1.2 degrees from 0.5
- Reload time to 2 seconds from 600
- Max targeting range to 500 meters from 600
- Traverse speed to 0.002 from 0.0015
- Idle rotation disabled by default

### Large Grid Missile Turret
- Fire rate to 360 RPM from 90
- Shot deviation to 1 from 0.5
- Traverse speed to 0.0015 from 0.001
- Idle rotation disabled by default
---
- Required construction component cost to 20 from 35
- Optional construction component cost to 40 from 15
- Required steel plate cost to 20 from 10
- Optional steel plate cost to 50 from 30
- Bounding box from 3x3x3 to 1x3x1
  - This change is not backwards-compatible and requires duplicating the cubeblock definition while hiding the original in build menu.

*Dev note: buffed survivability against return fire and powerful volleys makes a good budget artillery.*

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
- Shot deviation to 0.2 degrees from 0.25
- Reload time to 1.6 seconds from 4
- Targeting Range to 800 meters from 600
- Idle rotation disabled by default

*Dev note: this makes the AC turret competitive with large grids, even on small grids. It is your best anti-air defense.*

## Assault Cannons
- Damage from 4000 to 1800
- Projectile max range to 1600 meters from 1400
- Projectile explosion FX disabled
- Explosion VFX size to 0.4 meters from 2

### Small Grid Assault Cannon
- Reload to 2 seconds from 6
- Shot deviation to 0.25 degrees from 0.2

### Small Grid Assault Cannon Turret
- Reload to 1.5 seconds from 6
- Shot deviation to 0.35 degrees from 0.5
- Targeting range to 1000 meters from 600
- Idle rotation disabled by default
- Required construction component cost to 50 from 60
- Metal grid cost to 20 from 10

*Dev note: slight increase in the resource cost of assault cannons due to their general power level. Block health is unchanged.*

### Large Grid Assault Cannon Turret
- Reload to 2.667 seconds from 6
- Shot deviation to 0.6 degrees from 0.35
- Required construction component cost to 180 from 200
- Metal grid cost to 50 from 30
- Targeting range to 1200 meters from 800

## Artillery Cannons
- Armor piercing damage to 0 from 17000
- Explosive damage to 4000 from 0
- Projectile speed to 400 m/s from 500
- Explosive splash radius to 1.5 meters from 3
- Projectile max range to 2400 meters from 2000

### Artillery Cannon
- Reload to 4 seconds from 12
- Shot deviation to 0.5 degrees from 0.15
- Superconductor cost to 2 from 0

### Artillery Cannon Turret
- Fire rate to 90 RPM from 80
- Reload to 4.5 seconds from 12
- Shot deviation to 0.75 degrees from 0.3
- Superconductor cost to 5 from 0
- Targeting range to 1600 metres from 800

## Railguns

### Small Grid Railgun
- Projectile max range to 3600 meters from 1400
- Projectile speed to 1200 m/s from 1000
- Damage increased to 12000 from 8000
- Recoil force to 15000 from 30000
- Capacitor charge to 0.013 MWh from 0.016
- Recharge rate to 10.5 MW from 3.2
- Superconductor cost to 25 from 20
- Power cell cost to 20 from 10

*Dev note: Changes to the capacitors reduce weapon cycle time to 4.5 seconds from 16.5. Reload time now reflects this accurately.*

#### Small Railgun Slug
- Production time to 12 seconds from 8
- Slug Iron ingot cost to 20 from 4
- Nickel ingot cost to 4 from 0.5
- Silicon ingot cost to 8 from 5
- Cobalt ingot cost to 3 from 0
- Uranium ingot cost to 2 from 0.2

### Large Grid Railgun
- Projectile max range to 5000 meters from 2000
- Projectile speed to 2500 /s from 2000
- Reload time to 8 seconds from 4
- Shot delay to 1 second from 2
- Capacity to 0.6 MWh from 0.5
- Recharge draw to 300 from 38

*Dev note: Changes to the capacitors reduce weapon cycle time to ~10 seconds from 49.5. Reload time now reflects this accurately.*

#### Large Railgun Slug
- Production time to 20 seconds from 12
- Iron ingot cost to 100 from 20
- Nickel ingot cost to 15 from 3
- Silicon ingot cost to 40 from 30
- Gold ingot cost to 0.5 from 0
- Uranium ingot cost to 12 from 1

### Small Grid Turret Controller
- Targeting range to 1200 meters from 600

### Large Grid Turret Controller
- Targeting range to 1600 meters from 800

### Miscellaneous
- Target scanning distance to 3000 meters from 2000
- Target scanning angle to 45 degrees from 25
- Bulletproof glass integrity to 90 from 60