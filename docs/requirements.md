# requirements:
- sense person walking by
- energize coil
- sense projectile leaving the coil
- app
  - enable / disable auto-fire
  - fire on command
- this will be in a tree, it must catch the tree on fire:
  - consider housing
  - consider parts used (ie less to zero custom h/w)
  - s/w protection (ie don't keep coil on very long)

# parts
- control board
  - esp32 based (or pi)
    - (adafruit feather)[https://www.adafruit.com/product/5400]
  - need to drive enough current for coil (relay, mosfet)
    - (relay)[https://www.adafruit.com/product/3191]
    - (mostfet)[https://www.adafruit.com/product/5648]
  - short range motion sensor
  - long range motion sensor
    - (adafruit)[https://www.adafruit.com/product/189]
  - power? tbd
  - coil (motor wire, tube)
  - hammer
  - projectiles
  - spring? 2nd coil?

# plan
- figure out rest of parts
- check voltages (review)
- plan s/w
  - requirements
  - set up simulator (if exists)
  - architecture
  - lay out steps (simplest first, then build)
    - read motion sensor
    - drive relay
