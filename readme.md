# Dependencies

    - Modular Encounter System
    - Weapon Core
    - Defense Shields
    - Aryx Weapon Enterprises
    - Recolorable Thrusters

# Automatic Protection System (**APS**)

> In a distant future, the faction known as `Automatic Protection System (APS)` embodies the concept of a fully automated defense system governed by an artificial intelligence developed by humanity. Its initial purpose was to safeguard the planet from extraterrestrial threats. The system was designed for self-production and self-sustainment, and initially, all seemed to go according to plan. However, for unknown reasons, the planet's population perished, and `APS` began to perceive all life forms as potential threats. Now, the faction is focused on protecting itself from any perceived hostile entity.

### Faction CEO `Core`

> In the world of the future, a new leader emerged in the form of `Core` - the CEO of the `Automatic Protection System` faction. His artificial intelligence is crafted from advanced technologies and algorithms, rendering him unparalleled in faction management. Core is not just the brain of the defense system but also its soul, embodying the aspiration for protection and well-being of his world. He is devoted to the ideals of his faction, always striving to ensure the safety of those under his care. `Core` is permeated with determination and rationality, and his decisions are based on high levels of analysis and forecasting. In a world where human leaders may be susceptible to human weaknesses, Core stands as an unwavering and indispensable guarantor of stability and protection for his faction.

## Easy Encounters

### _Rogue Sentry_ (**D-0-0**)

> In the world of the future, beyond the control of the main artificial intelligence of the Automatic Protection System (APS) faction, there exists a lone drone known as the "Rogue Sentry". Its sole purpose is to seek out and destroy any sources of energy that it deems a threat to its existence. Doomed to an endless search, it roams through desolate landscapes, hunting for any signs of energy. Though its weaponry may be weak, it is still capable of inflicting harm upon those who dare to stand in its way. Cut off from communication with Core, the Rogue Sentry is an obsessed hunter, wandering in relentless darkness, posing a threat to anything that crosses its path.

#### Features

-   [x] Threat Score: `0`
-   [x] Spawn Cooldown: `15min`-`60min`
-   [x] Combat Phase: `true`
-   [x] Peace Phase: `true`
-   [x] Line of Sight Detection Range: `1000m`
-   [x] Movement Detection Range: `3000m`
-   [x] Movement Detection Score: `1000`
-   [x] Retreat on
    -   [x] Remote Control Health (`80%`)
    -   [x] No Weapon
-   [x] Combat Range
    -   [x] PD Laser: `500m`

### _Scout_ (**D-1-1**)

> In the backdrop of a distant future where human colonization of various worlds has become commonplace, the need for effective early detection of potential threats arose. Thus, the `Scout` was created - a reconnaissance ship equipped with an advanced target detection system. Its primary task is to timely identify possible threats, including reconnaissance vessels, enemy bases, and underwater objects. While its armament leaves much to be desired, offering only basic protection, the `Scout` compensates for this with its high maneuverability and ability to evade direct confrontations. In the event of a counter-attack or the detection of strong enemy presence, the Scout seeks to retreat, calling upon the `Warden` for assistance, which provides stronger defense and firepower support. Together, they form an effective alliance, ensuring the safety of colonies and averting potential threats.

#### Features

-   [x] Threat Score: `0`
-   [x] Spawn Chance: `75%`
-   [x] Combat Phase: `true`
-   [x] Peace Phase: `true`
-   [x] Broadcast Detection Range: `5000m`
-   [x] Line of Sight Detection Range: `1800m`
-   [x] Movement Detection Range: `2500m`
-   [x] Movement Detection Score: `1000`
-   [x] Retreat on
    -   [x] Remote Control Health (`80%`)
    -   [x] No Weapon
-   [x] Combat Range
    -   [x] Chaingun: `1200m`
-   [ ] Abilities
    -   [ ] Spawn `Warden` (600s cooldown)
    -   [ ] Try to call assistance from `Warden` (300s cooldown)

### _Warden_ (**D-1-2**)

> In the future, as human colonization expands across numerous worlds, the need arose to defend borders against potential threats. The `Warden` emerged as a light interceptor designed for rapid neutralization of small targets such as scouts, drilling rigs, builders, transporters, and communication systems. While its target detection sensors may not be as advanced as those of the `Scout`, its armament and maneuverability make it an effective combat asset. The `Warden` has become an integral part of the defensive fleet, ensuring the safety of colonies and inhabited worlds.

#### Features

-   [x] Threat Score: `50`
-   [x] Spawn Chance: `50%`
-   [x] Combat Phase: `true`
-   [x] Peace Phase: `true`
-   [x] Broadcast Detection Range: `2500m`
-   [x] Line of Sight Detection Range: `1800m`
-   [x] Retreat on
    -   [x] No Weapon
-   [x] Combat Range
    -   [x] Chaingun: `1200m`
    -   [x] Cannon: `4000m`
