# Ammo Check Animation Integration

This is for animators who want custom ammo check animations to play.

## Requirements

In your weapon hud section, define these keys:
```
[wpn_m4a1_tacticool]
hud = wpn_m4a1_tacticool_hud
snd_ammo_check          = click ; optional, plays when anm_ammo_check runs
snd_ammo_check_no_mag   = click ; optional, plays when anm_ammo_check_no_mag runs
snd_ammo_check_empty    = click ; optional, plays when anm_ammo_check_empty runs

[wpn_m4a1_tacticool_hud]
anm_ammo_check           = m4al_mag_check ; default mag check with semi-full magazine
anm_ammo_check_no_mag    = m4a1_mag_none ;  plays when no mag in weapon
anm_ammo_check_empty     = m4a1_mag_empty ; plays when mag in weapon and empty
```