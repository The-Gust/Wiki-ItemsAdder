# Can't write in chat and can't move

## Towny

{% hint style="warning" %}
If you have problems with vehicles and you're using Towny plugin open Towny config.yml and remove Slime from here:
{% endhint %}

```yaml
town_mob_removal_entities: Monster,Flying,Shulker,SkeletonHorse,ZombieHorse
```

## Mob Farm Manager

If you own [Mob Farm Manager ](https://www.spigotmc.org/resources/mob-farm-manager-supports-1-7-10-up-to-1-16-hopper-support.15127/)plugin please make sure to check if you set any entity type **SLIME** rule, this may remove the slime which is part of the vehicle and cause this bug.

## Other mobs removal / grouping / merge plugins

Please remove any group/merge/removal feature on entity type **SLIME**.

