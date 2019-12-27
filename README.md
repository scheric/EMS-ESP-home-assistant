# EMS ESP Home Assistant
Custom component for receiving mqtt values from ems-esp. I made this for clearing up the configuration.yaml files. 
 

# This project is in beta state

### my wishlist

- [ ] Add all received mqtt states.
  - [x] icons 
  - [x] sensors
  - [ ] switches
  - [ ] scripts
  - [ ] climate
  - [ ] binary sensors
  - [ ] optional kW calculation
- [ ] Add sending topics
- [x] Add configurable topic
- [ ] Create configurable data sets.
- [x] Add configurable name.
- [ ] Add to Home Assistant.


### How to use this

1. Create an `custom_components` folder located inside the Home Assistant `config` folder.
2. Copy the folder `ems-esp` into the `custom_components` folder. 
3. Add the yaml code below to your `configuration.yaml`
```yaml
sensor: 
  - platform: ems_esp
    name: EMS
    base_topic: home
```
4. reboot Home Assistant
