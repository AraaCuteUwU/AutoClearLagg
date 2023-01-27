# AutoClearLagg
The plugin you need to keep your server lagg free! 


# Features
- [x] Enable/Disable Mobs & Items clearing
- [x] NEW: Exempt entities from clearing
- [x] Configurable Timer
- [x] Editabe Messages

# config.yml
```---
# AutoClearLagg (ACL) Config

# Seconds between each clear lagg
seconds: 300

# Entities to clear
clear:
  items: true
  mobs: true
  exempt: # Array of entities not to clear
    - Zombie
    - Pig

messages:
  time-left: "§cEntities will clear in {SECONDS} seconds"
  entities-cleared: "§cCleared a total of {COUNT} entities"

# Countdown times
times: [60, 30, 15, 10, 5, 4, 3, 2, 1]
...
