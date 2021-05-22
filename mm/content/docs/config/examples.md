---
title: "Controller & Ports Examples"
description: "Example of all the port's features inside the config file."
lead: "Example of all the port's features inside the config file."
date: 2020-10-06T08:49:31+00:00
lastmod: 2020-10-06T08:49:31+00:00
draft: false
images: []
menu:
  docs:
    parent: "config"
weight: 650
toc: true
---
```json
{
  "controllerId": "mastermachine",
  "name": "Master Machine",
  "textureOverride": "minecraft:block/red_mushroom_block",
  "ports": [
    {
      "type": "masterfulmachinery:items",
      "textureOverride": "minecraft:block/cactus_side",
      "name": "Item",
      "id": "masteritem",
      "data": {
        "rows": 3,
        "columns": 3
      }
    },
    {
      "type": "masterfulmachinery:energy",
      "name": "RF Energy",
      "id": "battery",
      "data": {
        "capacity": 1000000000
      }
    },
    {
      "type": "masterfulmachinery:fluids",
      "name": "Fluid",
      "id": "tank",
      "data": {
        "capacity": 10000
      }
    },
    {
      "type": "masterfulmachinery:mekanism_gas",
      "name": "MekGas",
      "id": "mekgas",
      "data": {
        "capacity": 100000
      }
    },
	{
      "type": "masterfulmachinery:mekanism_slurry",
      "name": "MekSlurry",
      "id": "mekslurry",
      "data": {
        "capacity": 1000000
      }
    },
    {
      "type": "masterfulmachinery:create_rotation",
      "name": "CreateRotation",
      "id": "spinny",
      "data": {
      }
    },
    {
      "type": "masterfulmachinery:pncr_pressure",
      "name": "PneumaticcraftPressure",
      "id": "pncrair",
      "data": {
        "volume": 5000,
        "dangerPressure": 10,
        "criticalPressure": 30
      }
    },
	{
	  "type": "masterfulmachinery:astral_starlight",
      "name": "Starlight",
      "id": "starlight",
      "data": {
        "capacity": 1000
      }
    }
  ]
}
```